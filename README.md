# Udacity-capstone-Project
 Using machine leanring for Quora Insincere Questions Classification

# Project Overview
Social media platforms, online communities sharing knowledge, and many other public websites on Internet have become increasingly known for many problems related to the users’ unethical comments, cyberbullying, etc.
And since manually supervising comments and discussions can be cumbersome regarding the large volume of comments, companies often have to ask employees to take time away from their regular work to sift through comments or taking other measures. This clearly emphasises the need to automate the process of comments classification.
In this project I have trained a machine learning model that is capable of classifying unethical comments using hundreds of thousands of ‘Quora’ labelled comments.
This project is proposed by ‘Quora’ as a ‘Kaggle’ competition.

#Problem Statement
The goal is to handle non-ethical comments, in order to improve online conversation on Quora. This is done by identifying them and flagging them as insincere question. An insincere question is defined as a question intended to make a statement rather than look for helpful answers.
The process for solving such problem would be to use a supervised machine learning algorithm (many of them were tested in this project but the final model was a convolutional neural network) that will learn the patterns from the labelled comments.
The final model is supposed to, given a random comment, be able to classify it as ethical (good) or non-ethical (insincere).
