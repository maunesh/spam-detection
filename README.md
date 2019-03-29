# spam-detection

## Introduction
Spam detection is one of the major applications of Machine Learning in the interwebs today. Pretty much all of the major email service providers have spam detection systems built in and automatically classify such mail as 'Junk Mail'.

In this project, I am using the Naive Bayes algorithm to create a model that can classify a dataset of SMS messages as spam or not spam, based on the training. 

I am using [SMS Spam Collection Data Set](https://archive.ics.uci.edu/ml/datasets/SMS+Spam+Collection) from UCI Machine Learning Repository. The SMS Spam Collection is a public set of SMS labeled messages that have been collected for mobile phone spam research.

The model will classify messages as 'spam' or 'not spam'. 

One of the major advantages that Naive Bayes has over other classification algorithms is its ability to handle an extremely large number of features. In this case, each word is treated as a feature and there are thousands of different words. Also, it performs well even with the presence of irrelevant features and is relatively unaffected by them. The other major advantage it has is its relative simplicity. Naive Bayes' works well right out of the box and tuning it's parameters is rarely ever necessary, except usually in cases where the distribution of the data is known. It rarely ever overfits the data. Another important advantage is that its model training and prediction times are very fast for the amount of data it can handle. 

Below is are some evaluation metrics of Multinomial Naive Bayes classifier on SMS Spam Collection Dataset:

**_Accuracy score_**:  0.9885139985642498
**_Precision score_**:  0.9720670391061452
**_Recall score_**:  0.9405405405405406
**_F1 score_**:  0.9560439560439562
