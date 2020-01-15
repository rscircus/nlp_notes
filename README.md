# Natural Language Processing Notes/Quizzes

It turns out languages are difficult.

Not only for hearing disabled people (like me), but also for machines. Recently, I found a lovely course by [Dan Jurafsky](http://www.stanford.edu/people/jurafsky) and [Christopher Manning](http://nlp.stanford.edu/manning/), which was one of the first courses on Coursera generously provided by [Stanford's NLP Group](https://twitter.com/stanfordnlp). Coursera, it seems, slashed a bunch of courses during a pivot to become profitable. This course was one of them. Therefore, here the attempt to provide some content to **test yourself and your understanding of the lectures**, sorted by the list of topics.

**Feel free to fork this repo.** The questions will be in the `master` branch and _my answers_ in the `answers` branch. However, it might make sense for you to create your own `answers` branch.

## 📒 Outline and Basic Information

- Stanford's website: https://web.stanford.edu/~jurafsky/NLPCourseraSlides.html
- (Youtube) video content:https://www.youtube.com/playlist?list=PLQiyVNMpDLKnZYBTUOlSI9mi9wAErFtFm

## 📈 Progress

Here an empty 'TODO-list' to monitor your progress.

- [X] 1 Introduction
- [ ] 2 Basic Text Processing
- [ ] 3 Minimum Edit Distance
- [ ] 4 Language Modeling
- [ ] 5 Spelling Correction
- [ ] 6 Text Classification
- [ ] 7 Sentiment Analysis
- [ ] 8 Maximum Entropy Classifiers
- [ ] 9 Information Extraction and Named Entity Recognition
- [ ] 10 Relation Extraction
- [ ] 11 Advanced Maximum Entropy Models
- [ ] 12 POS Tagging
- [ ] 13 Parsing Introduction
- [ ] 14 'Instructor Chat'
- [ ] 15 Probabilistic Parsing
- [ ] 16 Lexicalized Parsing
- [ ] 17 Dependency Parsing
- [ ] 18 Information Retrieval
- [ ] 19 Ranked Information Retrieval
- [ ] 20 Semantics
- [ ] 21 Question Answering
- [ ] 22 Summarization
- [ ] 23 'Instructor Chat 2'

_Note that the videos 'almost' match the slides shown on Stanford's website due to the instructor chats!_

## 🗒️ Notes

## 1 Introduction - [video](https://youtu.be/3Dt_yh1mf_U)

### Summary

The very first lecture motivates the subject, describes the state of the art and already shows up a set of solved and difficult problems/examples/challenges. Further, we see an outline of the key theories and methods which we'll meet in this course. And also a set of skills which you need to basically start it, i.e., Linear Algebra, Probability Theory and some coding skills.

### Quiz:

- [X] Name a few examples where your everyday life is made easier by 'Language Technology'.
- [X] Do you know what field inside of NLP is represented in your everyday-life-case(s)? (If not, try to find out).
- [X] Why do you think the hard applications/problems are hard? (Some of the hard NLP problems: Paraphrase, Summarization, Dialog)
- [X] What is the 'general approach' in NLP?

### Answers:

#### Name a few examples where your everyday life is made easier by 'Language Technology'.

- Most search engines try to anticipate what I'm going to type.
- My phone keyboard does too, actually.
- At work I actually use NER (Named Entity Recognition). 🙉🙊🙈
- All the CORP-HERE-translate services.

#### Do you know what field inside of NLP is represented in your everyday-life-case(s)? (If not, try to find out).

- Most search engines try to anticipate what I'm going to type.

Probably this is some kind of frequency, which is probably even localized? Probably it's even personalized. 😱 Markov Chains come to my head somehow, but I forgot how they work in detail - something conditional probability-ish.

- My phone keyboard does too, actually.

Some thing as above, I guess.

- At work I actually use NER (Named Entity Recognition). 🙉🙊🙈

Here I understand this a bit. So there is some kind of statistical language model which tags the text after parsing it. I'm using these tags (entity labels) to find the interesting information. The trick here is to train the models well with an interesting question in mind.

- All the CORP-HERE-translate services.

Machine Translation. This was covered in the lecture in the yellow fields as far as I remember.

#### Why do you think the hard applications/problems are hard? (Some of the hard NLP problems: Paraphrase, Summarization, Dialog)

So, I remember ambiguity being a big problem. Sometimes it is even hard for humans. Like for instance to understand sarcasm/irony. Then there were a bunch of other problems which relate to having knowledge about the world.

#### What is the 'general approach' in NLP?

Create a probabilistic language model and apply it to the problem. ☺️

