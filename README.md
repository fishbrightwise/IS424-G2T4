# IS424-G2-T4
 Data Mining & Business Analytics Project

## Depression in Social Media
### Purpose
The objectives of this project are:
1. Explore mental health concerns via social media, focusing on depression’s prevalence and impact.
2. Possibly assess how economic factors—inflation, financial crises, and the pandemic—affect mental well-being.
3. Detect potential underlying causes and bring more attention to them

### Contents
Within this repository, you will find the following IPYNB notebooks:
1. Data Processing
    1) Reddit Depression Dataset Data Processing 
    2) 1.6 Million Dataset Data Processing
    3) Mental Health Dataset Data Processing

2. Reddit Depression Dataset Exploratory Data Analysis

3. Models & Methods
    1) Decision Trees
        1. Gradient Boosting (old)
        2. Gradient Boosting
    2) Naive Bayes
    3) Logistic Regression
    4) Long Short Term Memory (LSTM)

4. Model Applications
    1) Classifying new Data with LSTM Model
    2) Classifying new Data with Logistic Regression Model

5. Combining all Labeled Datasets & VADER Sentiment Analysis

6. Advanced Analysis
    1) EDA For Research
    2) Insights
    3) Gradient Boosted Labelled Data Analysis
    4) ngram
    5) Further Internal Attribute Analysis
    6) Sentiment140 Data Analysis

### Datasets
- Reddit Depression Dataset by Rishabh on Kaggle. <br>
https://www.kaggle.com/datasets/rishabhkausish/reddit-depression-dataset

- Sentiment Analysis Mental Health Tweets 2017-2023 by Zee M on Kaggle. <br>
https://www.kaggle.com/datasets/zoegreenslade/twittermhcampaignsentmentanalysis

- Sentiment140 dataset with 1.6 million tweets by Μαριος Μιχαηλιδης KazAnova on Kaggle. <br>
https://www.kaggle.com/datasets/kazanova/sentiment140

### How to use
1. Prepare the data:
    1) Download the data sources from their respective origin points mentioned above.
    2) Add in the datasets from the downloaded files into the /data folder.
        * Specifically for the Mental Health Tweets dataset, we are specifically used the Sentiment_Scored variant.
2. Process the data:
    1) Run notebooks 1) through 2) to prepare the processed data for modelling purposes.
3. Modelling (Optional):
    1) To see the inner-workings of each model, run any of notebooks 3) individually from start to end
        * Running these notebooks is not mandatory for the classification and subsequent analysis.
4. Apply the Model:
    1) Run notebooks 4.2) and 5) in order to obtain the new labelled corpus of data.
5. Analyze the data:
    1) Run notebooks 6) in any order depending on what form of analysis you are looking.
