#### 1. Which of the following is true about word2vec model?
##### Ans: It requires some text corpora for training.
#### 2. How can you train word2vec model?
##### Ans: 
- By learning to predict context (neighboring words) given one word.
- By minimizing crossentropy (aka maximizing likelihood).
- By applying stochastic gradient descent.
- By learning to predict omitted word by it's context.
#### 3. Here's an online demo of word2vec model. Let's use it to find synonyms for rare words. Don't forget to choose English GoogleNews model. Which of the following words is in top 10 synonyms for "weltschmerz".
##### Ans: despair
#### 4. Which of the following is an appropriate way to measure similarity between word vectors v1 and v2? (more = better)
##### Ans: 
-||v1 - v2||
- cos(v1,v2)