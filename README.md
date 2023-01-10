# Sentiment-Analysis
The objective of this project is to detect hate speech in tweets. For the sake of simplicity, we say a tweet contains hate speech if it has a racist or sexist sentiment associated with it. So, the task is to classify racist or sexist tweets from other tweets.
# Project Pipeline
The various steps involved in the Machine Learning Pipeline are :
• Import Necessary Dependencies
• Read and Load the Dataset
• Exploratory Data Analysis
• Data Visualization of Target Variables
• Data Pre-processing
• Transforming Dataset
• Function for Model Evaluation
• Model Building
• Conclusion
Among all these, training the machine learning model is the most computationally intensive task.
Now if we talk about training the model, which generally requires a lot of computational power, the process could be frustrating if done without the right hardware. This intensive part of the neural network is made up of various matrix multiplications
# Data Set Description
Formally, given a training sample of tweets and labels, where label ‘1’ denotes the tweet is racist/sexist and label ‘0’ denotes the tweet is not racist/sexist,our objective is to predict the labels on the given test dataset.
• id : The id associated with the tweets in the given dataset.
• tweets : The tweets collected from various sources and having either positive or negative sentiments associated with it.
• label : A tweet with label ‘0’ is of positive sentiment while a tweet with label ‘1’ is of negative sentiment.
