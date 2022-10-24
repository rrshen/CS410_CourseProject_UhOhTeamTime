# Project Proposal: Matching Questions and Responses

## Members

Rachel Shen (rrshen2) (Captain)

## Topic

My free topic is to create a software application that will use sentiment analysis and pattern matching to rank the appropriateness of follow-up reactions to question-answer pairs. For example, if "How are you?" were a question, "Not so great" were the answer, and I had a list of possible responses `[ "Great!", "That's pretty cool", "Oh no!", "I'm so sorry", "What happened?", ]`, I would want to rank "Oh no!", "I'm so sorry", and "What happened?" above the other two options. 

## Inspiration
Many games allow players to choose dialogue options so that they will feel more involved in how the story unfolds. However, I've noticed that some games will have the non-player characters react in a very neutral way that would be acceptable for both dialogue choices so that the player feels engaged without the developer having to do any extra work with branching. However, this often results in stilted interactions between player and non-player characters. It can also give the player the feeling that their choices don't matter, which is generally undesirable when playing a game.

Even games where the player's choices do impact the plot tend to only allow players a limited degree of freedom, because the developer cannot account for the sheer number of possible responses. For example, there will be one or two choices the player can make, and each of those choices is directly linked to certain statistics and later events.

To me, this project is interesting, because it would give developers the freedom to allow players to input any text, and the program will do its best to match the submitted text to a character's response. If each of the responses were linked to a different set of future options in the game, then the player would have a lot more perceived freedom without the developer having to do much more work.

I also briefly searched up 'free chatbot', and the first one I was able to find online replied to my questions but did not ask any of its own or ever elaborate on its replies. This made the conversation feel very unnatural, as most human interactions are slightly more stochastic in structure. If the bot were able to ask random questions and react according to the other party's response instead of only responding to questions, it would feel much less robotic. Obviously, relevant questions would be a further improvement, but I think this example sufficiently explains how my project could help improve existing chatbots.

## Implementation

I plan to use Python to complete my project.

Because my project uses similar logic as the web search ranking problem as well as chatbots, I will first collect research documents and example chatbot implementations for reference. I may also search for sentiment analysis APIs, because I may want to give more weight to words like "never" and "always" when creating the algorithm for matching reactions to responses. 

The lecture on multi-level judgements such as nDCG may also be useful, as I can see instances where a number of different reactions may be equally appropriate and another few may be strange, whereas the vast majority are completely inappropriate. 

I am not sure about there being any existing datasets that I can use. I am thinking that I will have to create my own, as I don't recall reactions to responses being a major topic of study, although I may find myself surprised during the research process.

I think I will also need to find source code for the implementation of sentiment analysis or a free API that will analyze sentiments online.

I expect to be able to match at least a small group of sample responses to appropriate reactions by the end of this project, although it would be great if I had time to code it so that different questions with the same response could result in reactions being ranked differently.

## Evaluation

My work will have to be evaluated empirically. Similar to the ranking problem, there are no objective standards for what response is most appropriate. In fact, the core problem is a ranking problem, with the response being the query and the set of reactions being the corpus. However, it is different from simple ranking in that we do not want to react by simply repeating the same words in the query; instead, there will be a yet unknown relationship that we find between the responses and reactions.

## Workload

It will probably take at least 3-5 hours to gather research on chatbot and sentiment analysis implementations and to organize materials from what we've learned about relevance rankings. The creation of a well-sized set of questions, responses, reactions, and relevance rankings could also take another 3-5 hours. I will have to come up with an algorithm for scoring the reactions. I am thinking that I may want to find a free sentiment analysis API or some open source code so that I can look for relationships between sentiments between responses and appropriate reactions. The process of integrating sentiment analysis into my project could take 5-10 hours, and comparing the relationships in order to match them could take another few hours. It may be best for me to score reactions without considering the question asked and try to take the question into consideration only if I have time later. If I spend a long time debugging or if I have missed a step in calculating the workload, this project could easily take much longer than 20 hours. As there is only myself on this team, I think that this set of steps is adequate in justifying that I will need to work at least 20 hours on this project. 
