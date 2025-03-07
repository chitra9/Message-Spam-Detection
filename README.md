# Spam Message Detection using Machine Learning

This project implements a spam detection system using Natural Language Processing (NLP) and Machine Learning (Naive Bayes Classifier). It classifies text messages as Spam (1) or Not Spam (0) based on their content.

## Project Overview
- Uses text classification techniques to identify spam messages.  
- Trained on the SMS Spam Collection dataset.  
- Converts text messages into numerical features using CountVectorizer (Bag of Words).  
- Implements a Multinomial Naive Bayes classifier to detect spam.  

## Technologies Used
- Python  
- Pandas  
- Scikit-Learn  
- CountVectorizer  
- Naive Bayes Classifier  

## Dataset
The dataset consists of two columns:  
- Label → "ham" (Not Spam) or "spam" (Spam)  
- Message → The actual text content of the message  

Example:  

| Label | Message |
|-------|---------|
| spam  | Win a free iPhone now! |
| ham   | Hey, how are you? |
| spam  | Congratulations! You've won a lottery. |

Before training, labels are converted:  
- Spam = 1  
- Not Spam (Ham) = 0  

## Model Workflow
1. Load the dataset (spam.csv).  
2. Preprocess the text data (remove unnecessary columns, convert labels).  
3. Convert text into numerical format using CountVectorizer.  
4. Split the dataset into training and testing sets.  
5. Train the Naive Bayes classifier.  
6. Evaluate model accuracy.  
7. Test the model on new messages.  

## Model Performance
- Accuracy: ~98%  
- Algorithm: Naive Bayes  
- Feature Extraction: Bag of Words (BoW)  

## Installation and Setup

### Clone the Repository

git clone https://github.com/your-username/Message-Spam-Detection.git
cd Message-Spam-Detection
