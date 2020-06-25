# Fake-News-Detector
The project is concerned with classification of news into Real And Fake News , that could be used to detect and filter out sites containing fake news for purposes of helping users to avoid being lured by clickbaits. 

## Implementation

This python project of detecting fake news deals with fake and real news.
Using sklearn, we build a TfidfVectorizer on our dataset. Then, we initialize a
PassiveAggressive Classifier and fit the model. In the end, the accuracy score
and the confusion matrix tell us how well our model fares.

## DataSets

Two datasets were collected. The first data has been collected from kaggle repository which
focuses on US-based presidential election from 2016. The second dataset has been collected manually from
news and articles sources from twitter,whatsapp and facebook mainly related to latest news
around corona virus in India , both fake and real news . 

For convenience, we shall use Dataset-1,”news.csv” for Kaggle website dataset and Dataset-2 ,”indian_news.csv” for our
manually collected data respectfully. Dataset-1 in this research include (6335 X 3), which means
6335 rows and three columns. Each Fake news has labels in the 3rd column. 

Dataset-2 includes (57 X 4), which means 57 rows and four columns.So the data is collected in
xlsx format as per the convenience or looking at the rate of data importing errors and then saved
as a csv file.
