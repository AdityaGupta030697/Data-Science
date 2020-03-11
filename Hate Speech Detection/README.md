### Twitter Sentiment Analysis
Sentiment Analysis refers to the use ofnatural language processing,text analysis,computational linguistics, andbiometricsto systematically identify, extract, quantify, and study affective states and subjective information. Sentiment analysis is widely applied tovoice of the customermaterials such as reviews and survey responses, online and social media, and healthcare materials for applications that range frommarketingtocustomer serviceto clinical medicine. (Source: Wikipedia)

The objective of this task is to detect hate speech in tweets. For the sake of simplicity, we say a tweet contains hate speech if it has a racist or sexist sentiment associated with it. So, the task is to classify racist or sexist tweets from other tweets. 

Formally, given a training sample of tweets and labels, where label '1' denotes the tweet is racist/sexist and label '0' denotes the tweet is not racist/sexist, your objective is to predict the labels on the test dataset.

Evaluation Metric:
The metric used for evaluating the performance of classification model is F1-Score.

Contest link: https://datahack.analyticsvidhya.com/contest/practice-problem-twitter-sentiment-analysis/    
(Source: AnalyticsVidhya.com)

Current results (using custom word2vec embeddings): 
| Model | F1-Score |
|---------------------|---------:|
| Logistic Regression |   0.6728 |
| SVM                 |   0.7388 |
| XGBoost             |   0.7092 |
