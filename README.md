# Movie-and-Political-Sentiment-Analysis-with-PySpark
Building a machine learning model using PySpark, TF-IDF, and logistic regression with elastic net regularization to perform sentiment analysis on IMDb rating review data and Tweets

# Objective
The objective of this project is to perform sentiment analysis on movie reviews and political tweets using PySpark and Logistic Regression with Elastic Net Regularization. The aim is to develop a machine learning model that can predict the sentiment of a given text accurately.

# Requirement 
Pyspark

# Algorithm
- Logistic Regression
- Elatic Net Regularization

# Methodology
- The project was divided into two main parts. In the first part, utilize PySpark to perform the preprocessing steps such as cleaning, tokenization, and stop-word removal. Then, then utilize the Term Frequency-Inverse Document Frequency (TF-IDF) technique to extract the features of the text data. The team then created a pipeline that utilized Logistic Regression with Elastic Net Regularization to train and fit the model on the IMDb rating review dataset. achieving an accuracy of 83.60% on the IMDb rating review dataset.
- In the second part, utilize the same model to perform sentiment analysis on political tweets from the 2016 election, focusing on Hillary Clinton and Donald Trump. collecting and cleaning the data and then used the same pipeline that was developed in the first part to predict the sentiment of the tweets. The team then evaluated the model's performance by analyzing the accuracy, precision, recall, and F1-score.

# Results
The team achieved an accuracy of 83.60% on the IMDb rating review dataset, indicating that the model could predict the sentiment of movie reviews with high accuracy. I also achieved an accuracy of 76.45% on the political tweets dataset, indicating that the model could also predict the sentiment of political tweets with moderate accuracy. I went ahead and compared the sentiment towards Donald Trump and Hillary CLinton during the 2016 Election, here is what I found

![image](https://user-images.githubusercontent.com/7029092/234103866-98d8a836-24d7-4ad5-b0f6-d7d16e3680a4.png)

# Conclusion
The project demonstrated the effectiveness of PySpark and Logistic Regression with Elastic Net Regularization in performing sentiment analysis on text data. The model developed by the team can predict the sentiment of movie reviews and political tweets with reasonable accuracy. The project's results can be applied in various domains, such as marketing, politics, and social media analysis.
