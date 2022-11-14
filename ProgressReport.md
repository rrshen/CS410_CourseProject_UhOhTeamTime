# Project Proposal: Matching Questions and Responses

## Tasks

- [x] Resource collection
  - Open source chatbots
    - https://github.com/gunthercox/ChatterBot
    - https://github.com/FORTFANOP/ChatbotVerse
  - Sentiment analysis APIs
    - https://www.twinword.com/api/sentiment-analysis.php
    - Video on sentiment analysis: https://youtu.be/kBoe56CfugY
  - My private MP2.3 repository 
    - https://github.com/rrshen/MP2.3_private
    
- [x] Data collection
  - Google form asking people to rank the appropriateness of reactions to responses to the question "How are you doing?"
    - https://forms.gle/pyXcjunn5DeLQLp76
    - https://docs.google.com/spreadsheets/d/1s3apLBxWJRFG5jkmzOnENAjwzOHSVa9an8pYPAfEWzg/edit?resourcekey=undefined#gid=1094134541

- [ ] Data organization into computer-readable document
  - In progress
    - Organized into spreadsheet with a matrix of possible combinations
    - https://docs.google.com/spreadsheets/d/1s3apLBxWJRFG5jkmzOnENAjwzOHSVa9an8pYPAfEWzg/edit?resourcekey=undefined#gid=1094134541

- [ ] Algorithm for scoring reactions

- [ ] Code
  - Created Colab notebook for final project
    - https://colab.research.google.com/drive/1MAT1Jzh2zQUpkCU0pKWeR9_FqM4SlvTc?authuser=1#scrollTo=4FIirLj0Ynrd
    - In progress

## Challenges

Because this is a niche topic, there don't seem to be any available databases for pairings or rankings. I had to create my corpus and potential 'queries' myself and present all of the options in a way that would allow people to rank them. Adding each new response and reaction took about five minutes by the time I reached a point I deemed satisfactory, and I only have a single question with 24 potential answers and 13 potential reactions to the answers, but the Google form consists of 338 questions, which took a very long time to create and is daunting for people to fill out.

I also realized during the data organization step that, because I created the form myself, it was very difficult to organize the data, and I duplicated or missed certain combinations of answers and follow-ups. This has since been rectified, but it took a few hours to aggregate the data into a matrix-like form, and I'm still not sure how I can turn a Google Sheets spreadsheet into a matrix of rankings.

Now that my data is mostly collected and organized, I'm also a little unsure about how to integrate my data and idea with the open source code on chatbots that I've found. It seems that a lot of them train with a neural network? I'm not totally sure how the steps for my project, code-wise, should go...
