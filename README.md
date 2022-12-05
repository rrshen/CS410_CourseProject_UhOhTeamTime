# Text-Based Game Enhanced By AI

Originally, my proposal was as described in ProjectProposal.md; I wanted to create a software application that will use sentiment analysis and pattern matching to rank the appropriateness of follow-up reactions to question-answer pairs. However, I spoke with the professor during Office Hours, and he inquired as to my motivation for this project. I explained that I had been inspired while playing text-based games, and Professor Zhai suggested that I use existing language models such as GPT-3 to improve text-based games rather than attempting to basically reproduce a functionality that existing advanced chatbots have already tried to implement. So instead of following through with my original plan, I have pivoted to enhancing a text-based game using AI. 

## Team Members

**Captain** Rachel Shen (rrshen2)

## Topic

My free topic is using a deep learning language model to increase the level of personalization involved in text-based games. This is interesting, because one limitation that text-based games have always had is the inherent lack of options. All of the possibilities that a player can choose from must be addressed during production, which means that if a character asks "How are you?", most games will give the player 1-2 similar options, because the other character has to respond, and if the player says something like "I've been bitten by a zombie", a generic "That's good to hear!" won't make much sense. As a casual enjoyer of games, it feels even more frustrating to have a choice between options that don't affect the other characters' responses at all, although it's not very fun to go through big blocks of text where you as the player cannot give any input either. An AI such as the GPT-3 Davinci model addresses these frustrations by allowing more free exchanges, because the AI acts as a human-like entity that can adjust its response depending on the player's choices. I chose the OpenAI API's GPT-3 Davinci model, because it was the most robust model that I found online. After running into problems integrating it with Ren'Py, a popular visual novel engine, I decided to use Google Colaboratory to run my text-based game. I expect to be able to play all the way through a short text-based game with reactive casual conversation as well as open-ended player input that directly impacts the gameplay. I will evaluate my work by playing through different endings.

## Programming Language

Python

## Main Results

- [x] Source Code
 - https://colab.research.google.com/drive/1MAT1Jzh2zQUpkCU0pKWeR9_FqM4SlvTc?usp=sharing
 - Credit to https://colab.research.google.com/github/interactive-fiction-class/interactive-fiction-class.github.io/blob/master/homeworks/text-adventure-game/Text_Adventure_Game.ipynb for guidance on how to build a text-based game in Colab and credit to OpenAI for the deep learning language model, GPT-3.
- [x] Demo
 - https://youtu.be/ipwioty3RhM
- [x] Self Evaluation
 - I originally set out to improve on chatbot functionality but pivoted to directly improving text-based games using a deep learning language model. Even then, I initially wanted to integrate OpenAI with Ren'Py, because Ren'Py is a well-established free visual novel engine that has allowed thousands of creators around the world to put out choose-your-own-adventure style games. However, I ran into conflicts with different dependencies between Ren'Py and OpenAI, so I turned to Colab instead. After that, I was able to create a text-based game that depends on the output of OpenAI, so I did achieve that goal. However, it was a much more limited game due to the lack of real infrastructure on Colab for creating a game, and it was not what I first envisioned. I would say that I fulfilled what I planned but that the plan itself changed drastically from the original.

## Workload

Though I did not end up using my self-collected dataset from the progress report, that took approximately five hours to create and another two or three to clean into a computer-readable format. I had also spent a couple of hours looking into free chatbot code documentation online as well as algorithms for machine learning at that point. It was during an Office Hours where I was explaining to the professor that my focus changed, and I spent another five or so hours after the pivot learning about OpenAI GPT-3, BigScience Bloom, watching tutorials on how to use the API with Colab, going through the website to find the extent of my options, and exploring the capabilities of different GPT-3 models (Davinci, Curie, etc.) in the OpenAI Playground. Finding a text-based game format to begin with also took at least five hours; I spent a long time debugging Python versions and downloading different modules onto my computer while trying to connect Ren'Py with the OpenAI API. I even reached out to the developer of the Ren'Py Visual Novel Engine and exchanged traceback photos over a period of five days, although my endeavor to connect a third-party API to the engine was ultimately unsuccessful. I then had to search for other options online. I settled on using Google Colaboratory, because I have used Colab before for CS 410 projects, I found code for a text-based adventure game in Colab online and was able to verify that it worked as expected, and I was able to play around with GPT-3 in another Colab file that I created shortly after creating my account. My API key also expired on December 1st, which further complicated my plans, as I had to get another email and phone number to start another free trial for this project. It then took me about ten hours to modify and debug the text-based adventure game code from the Colab project I found online to create a somewhat cohesive game that accomplishes the goals I set out to accomplish.

All in all, I definitely spent more than the 20 hours a 1-person group is expected to have spent on this final project.
