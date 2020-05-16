# News Headlines Dataset for Sarcasm Detection

![alt text](http://i.ytimg.com/vi/mSy5mEcmgwU/maxresdefault.jpg)

## Background of problem statement
To build a best accurate machine learning model which detects the sarcastic sentences.

## About the dataset
Studies in Sarcasm Detection mostly make use of Twitter datasets collected using hashtag based supervision but such datasets are noisy in terms of labels and language. Furthermore, many tweets are replies to other tweets and detecting sarcasm in these requires the availability of contextual tweets.

To overcome the limitations related to noise in Twitter datasets, this News Headlines dataset for Sarcasm Detection is collected from two news website. TheOnion aims at producing sarcastic versions of current events and we collected all the headlines from News in Brief and News in Photos categories (which are sarcastic). We collect real (and non-sarcastic) news headlines from HuffPost.

This new dataset has following advantages over the existing Twitter datasets:

* Since news headlines are written by professionals in a formal manner, there are no spelling mistakes and informal usage. This reduces the sparsity and also increases the chance of finding pre-trained embeddings.

* Furthermore, since the sole purpose of TheOnion is to publish sarcastic news, we get high-quality labels with much less noise as compared to Twitter datasets.

* Unlike tweets which are replies to other tweets, the news headlines we obtained are self-contained. This would help us in teasing apart the real sarcastic elements.

## Content in the dataset
Each record consists of three attributes:

 * is_sarcastic: 1 if the record is sarcastic otherwise 0

 * headline: the headline of the news article

 * article_link: link to the original news article. Useful in collecting supplementary data
 
## Link to the Dataset
https://www.kaggle.com/rmisra/news-headlines-dataset-for-sarcasm-detection

## Installation
Install the latest version of Anaconda for python 3 from this link (https://repo.anaconda.com/archive/) ,once you open the link, you'll find a long list of installers, choose the latest version and download the relevent OS installer and install it.

To download the ipynb file from GitHub-

Click on Raw
Then, press ctrl+s to save it as .ipynb
Open jupyter notebook
Go to location where you saved .ipynb file
Open that file and start executing
