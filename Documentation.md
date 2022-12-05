# Project Documentation

I spoke with the professor during office hours, and he inquired as to my motivation for this project. I explained that I had been inspired while playing text-based games, and he suggested that I use existing language models such as GPT-3 to improve text-based games rather than attempting to basically reproduce a chatbot. So instead of just creating a software application that uses sentiment analysis and pattern matching to rank the appropriateness of follow-up reactions to question-answer pairs, I have pivoted to the aforementioned topic.

## Main Results

- [x] Source Code
 - https://colab.research.google.com/drive/1MAT1Jzh2zQUpkCU0pKWeR9_FqM4SlvTc?usp=sharing
- [ ] Demo
 - A demo that shows your code can actually run and generate the desired results. If there is a training process involved, you don’t need to show that process during the demo. If your code takes too long to run, try to optimize it, or write some intermediate results (e.g. inverted index, trained model parameters, etc.) to disk beforehand.
- [x] Self Evaluation
 - I originally set out to improve on chatbot functionality but pivoted to directly improving text-based games using a deep learning language model. Even then, I initially wanted to integrate OpenAI with Ren'Py, because Ren'Py is a well-established free visual novel engine that has allowed thousands of creators around the world to put out choose-your-own-adventure style games. However, I ran into conflicts with different dependencies between Ren'Py and OpenAI, so I turned to Colab instead. After that, I was able to create a text-based game that depends on the output of OpenAI, so I did achieve that goal. However, it was a much more limited game due to the lack of real infrastructure on Colab for creating a game, and it was not what I first envisioned. I would say that I fulfilled what I planned but that the plan itself changed drastically from the original.
