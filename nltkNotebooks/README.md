Nltk Notebooks
==

> This repo contains various notebooks written by me for sentiment classifications and stuff using nltk.

**Presently the repo contains:**

1. My implementation of nltk's inbuilt Naive Bayes Classifier and Maximum Entropy Classifier on twitter data. You can view the Classifier file online [here](http://nbviewer.ipython.org/github/drreddy/python_skunkworks/blob/master/nltkNotebooks/nltk_sent_classifiers.ipynb)
2. My implementation of text summarizers one using words frequencies for ranking the sentences of the text and another using textrank (similar to pagerank). You can view the notebook file online [here](http://nbviewer.ipython.org/github/drreddy/python_skunkworks/blob/master/nltkNotebooks/nltk_summarizer.ipynb)


Local Installation
--------------
```sh
git clone https://github.com/drreddy/python_skunkworks.git
cd nltkNotebooks
ipython notebook
```

### Important Note:
#### 1. For tweets sentiment classification the training data the data is taken from sentiment140 site. To run the notebook you need to download the data and keep it in data folder in this repo