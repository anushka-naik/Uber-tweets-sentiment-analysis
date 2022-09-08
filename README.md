# Uber-tweets-sentiment-analysis

## About  
  
Twitter analysis is a widely used concept in order to examine the public opinion about a particular topic/event/company.A review of a person/customer is analyzed via the tweets which helps the companies to further understand what review does a customer has about the product or service provided by the company.


In this project, Tweets are extracted from the data set. The data of the tweet has to be cleaned and optimised as each tweet consists of unnecessary details like username,'RT', punctuations, special characters, digits, hashtags etc. These components are not required in the sentiment analysis and hence the dataset needs to be cleaned. The data is then visualised using word/tag clous-which is a visual representation of text data, which is often used to depict keyword metadata.
The sentiment analysis is then conducted and the score of sentiment of tweets is calculated. Varying degrees of positive or negative score is assigned based on the intensity of the tweet. Finally, Tweets are bifurcated in positive if total score is greater than zero and negative otherwise.

Now for checking the accuracy of this sentiment analysis we are using the classification algorithm Support Vector Machine and Naïve Bayes. 

## Result:

- Using Support Vector Machine algorithm and kernel as Linear, the accuracy obtained was 87.24 %.
- Using Support Vector Machine algorithm and kernel as Radial, the accuracy obtained was 85.23 %.
- Using Naïve Bayes algorithm, the accuracy obtained was 87.24 %.
