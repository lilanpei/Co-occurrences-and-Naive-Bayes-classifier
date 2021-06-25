# [Homework 1] Co-occurrences-and-Naive-Bayes-classifier

This homework will explore some basic techniques presented in the first two weeks of the course.

You will be invited to experiment with:

1. Co-occurrences
2. Naive Bayes classifier


Fill in the blanks with your own code and see how it works.

## 1. Co-occurrences
* Vocabulary

Get the list of words of documents in the category `news`.

### 1.1 Compute co-occurrence Matrix
Constructs a co-occurrence matrix for a certain window-size $n$ (with a default of
4), considering words $n$ before and $n$ after the word in the center of the window.
  * Explore co-occurences
  * Do the same for category ‘hobbies’.
### 1.2 Visualize the Vectors
Projects vectors into two dimensions and use it to plot the rows of the sliced matrix, using the technique of Principal
Component Analysis.
  * Extract the co-occurrence vectors for a given list of words.
  * Visualize the co-occurrence vectors for the given words.
## 2 Naïve Bayes Classifier
We will use the Movie Review dataset from https://www.kaggle.com/pankrzysiu/keras-imdb
It contains 50,000 highly polarized reviews, preprocessed, tokenized, indexed and stored into
numpy arrays.
* Load the training and test set.
### 2.1 Classifier

The classifier should be impelemted as a class with two methods: `train()` and `predict()`.
### 2.2 Evaluation
