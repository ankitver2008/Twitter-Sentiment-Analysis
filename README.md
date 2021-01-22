# Twitter-Sentiment-Analysis
In this project, a python program is written which uses NLTK library to predict the sentiment of tweet using naive bayes classification technique.

Problem Statement:

This data originally came from Crowdflower's Data for Everyone library.

The Data contains tweets about the early August 2016 GOP debate in Ohio compiled with the help of several contributors. The contributors attributed sentiment to the data as positive or negative and performed data categorization. Contributors were asked if the tweet was relevant, which candidate was mentioned, what subject was mentioned, and then what the sentiment was for a given tweet. Non relevant data has been removed.

As a part of analysisng the text data, a predictive model needs to be built that categorises the tweet as positive or negative.


Conlcusion:

In this project I used NaiveBayes Machine Learning algorithm performs for Sentiment Analysis. 
In this project, we can see that it works rather well for negative comments. The problems arise when the tweets are ironic, sarcastic has reference or own difficult context.

Consider the following tweet:
*"Muhaha, how sad that the Liberals couldn't destroy Trump.  Marching forward."*
As you may already thought, the words **sad** and **destroy** highly influences the evaluation, although this tweet should be positive when observing its meaning and context. 

To improve the evalutation accuracy, we need to take the context and references into consideration.
