# FakeNewsDetection
Fake News Detection with Python using Natural Language Processing
.

## Introduction
 With the rise of the social media platform it is easier for anyone to access information in 
real time, However, there are also people who also use social media platforms in the negative 
way to attain monetary gain by spreading fake news. Fake news often has the aim of damaging 
the reputation of a person or entity, or making money through advertising revenue. It is important 
that we have some mechanism for detecting fake news. 

The goal of this project is to create a model that inputs text and output whether the text is 
likely to be truthful or fake. All work is done on jupyter-lab.


## Dataset
You can download the dataset from https://www.kaggle.com/datasets/csmalarkodi/isot-fake-news-dataset.

The dataset contains two types of articles: fake and real News. This dataset was collected 
from real- world sources; the truthful articles were obtained by crawling articles from
2Fake News Detection with Natural Language Processing
Reuters.com (News website). As for the fake news articles, they were collected from different 
sources. The fake news articles were collected from unreliable websites that were flagged by 
Politifact (a fact-checking organization in the USA) and Wikipedia. The dataset contains 
different types of articles on different topics, however, the majority of articles focus on political 
and World news topics. The dataset consists of two CSV files. The first file named “True.csv” 
contains more than 12,600 articles from reuter.com. The second file named “Fake.csv” contains 
more than 12,600 articles from different fake news outlet resources. Each article contains the 
following information: article title, text, type and the date the article was published on. To match 
the fake news data collected for kaggle.com, we focused mostly on collecting articles from 2016 
to 2017. The data collected were cleaned and processed, however, the punctuations and mistakes 
that existed in the fake news were kept in the text.

## Evaluate text

Use function evaluate()

```
fakeNews = "This is a fake news"
evaluate(fakeNews)
```
