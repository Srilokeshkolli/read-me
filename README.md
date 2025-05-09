***Project Overview:-***


The goal of this project is to use supervised models of machine learning to identify real or fake news by examining the text of news items.

***Purpose and Key Functionalities:-***

This project's objective is to create a classification system that, using linguistic characteristics, can differentiate between real and fake news articles.  A number of crucial steps are involved in this project: importing and cleaning the dataset, preprocessing the text (removing stopwords, stemming, etc.), using TF-IDF to turn the cleaned text into numerical vectors, and then training four machine learning models: Multinomial Naive Bayes, Decision Tree, Random Forest, and Logistic Regression.  To assess each model's performance in identifying false information, metrics like accuracy, precision, recall, and F1-score are used.

***Setup and Dependencies:-***

Make sure you have the necessary libraries installed in order to run through this project:-

--> pandas

--> numpy

--> matplotlib

--> seaborn

--> nltk

--> sklearn (scikit-learn)

--> wordcloud

you can install them useing this following command:- pip install pandas numpy matplotlib seaborn nltk scikit-learn wordcloud

Also, download the necessary NLTK resources by running:-

--> import nltk

--> nltk.download('stopwords')

***Steps to Reproduce Results:-***

--> Open Machine_learning_final_project.ipynb, in Google Colab

--> Execute the cells sequentially, beginning with the TF-IDF transformation, preprocessing, and data import.

--> Continue with the evaluation and training of the model.  Code for splitting the dataset, training models, and printing performance metrics is included in the Google colab

--> Examine each model's printed accuracy, precision, recall, and F1-scores to compare outcomes.


