# Text-Classficiation-using-NB-LR

The notebooks contains implementations of Discrete Naive Bayes (DNB), Multinomial Naive Bayes (MNB), Logistic Regression with L2 regularization (all from scratch), and an SGDClassifer from scikit-learn for the task of text classification on the ENRON email dataset. 

The DNB model classifies on the bernoulli matrix while the MNB model classifies on the Bag of Words matrix, both of which have been created using CountVectorizer from sklearn

Prerequisite - Download the dataset

### Steps to execute code: 
1. Create a python 3.10 environment

2. Run the following commands to install necessary libraries 
	- pip install numpy
	- pip install scikit-learn
	- pip install ntlk

3. Extract the .zip dataset and the directories inside.

4. Write the path to the directories containing the ‘ham’ and ‘spam’ folders. The 4th block in the Jupyter Notebook takes in these paths to create subsequent Bernoulli and Bag of Words datasets. 

5. Run the notebook. 

The notebook also contains estimated run times for the evaluation functions. Note that I ran the code on my laptop so the times may vary for your run. (Faster hopefully!)
