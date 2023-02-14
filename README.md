# NLP-stackoverflow-tag-predict

## StackOverflow-Tag-prediction

Problem: Given the Title and body of a question on Stack overflow, predict the tags associated with the question.

<h1>Business Problem </h1>
<p style='font-size:18px'><b> Description </b></p>
<p>
Stack Overflow is the largest, most trusted online community for developers to learn, share their programming knowledge, and build their careers.<br />
<br />
Stack Overflow is a platform widely used by programmers, with over 50 million developers visiting the site each month to gain knowledge, share their expertise, and advance their careers. The website hosts a vast collection of questions and answers spanning a broad range of computer programming topics. Users can ask and answer questions, vote on content, and edit posts in a collaborative manner similar to a wiki or Digg. As of April 2014, Stack Overflow had over 4 million registered users and by late August 2015, it had accumulated more than 10 million questions. Based on the assigned tags, the most popular topics on the site are Java, JavaScript, C#, PHP, Android, jQuery, Python, and HTML.<br />
</p>

<p style='font-size:18px'><b> Source:  </b> https://www.kaggle.com/c/facebook-recruiting-iii-keyword-extraction/</p>

<h1> Objectives </h1>
1. Predict as many tags as possible with high precision and recall.<br>
2. Incorrect tags could impact customer experience on StackOverflow.<br>

## Project name: NLP-stackoverflow-tag-predict

### Strategy:

1. Libraries
2. Data Cleaning – Stage 1
3. Analysis of Tags
4. Tag Plots
5. Data Cleaning – Stage 2
6. Training Data
7. Testing Data
8. Machine Learning
9. Splitting the training Data
10. Tags Reduction
11. Removing no coverage
12. Featurizing data with TF-IDF vectorizer
13. Featurizing Labels
14. OneVsRest Classifier with SGDClassifier using TF-IDF

This project aims to predict tags for Stack Overflow questions using machine learning. The data was explored, cleaned, and preprocessed. The OneVsRestClassifier with logistic regression was used for classification, achieving a micro f1 score of 0.47. Hyperparameter tuning was performed, and the best value of C was found to be 0.01, resulting in precision of 0.7072, recall of 0.3376, and micro f1 score of 0.4571.
