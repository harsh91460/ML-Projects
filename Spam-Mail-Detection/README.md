# Spam Mail Detection using Machine Learning

## Project Description
This project builds a machine learning model to detect whether a message is spam or not. 
The model is trained on a dataset of SMS messages where each message is labeled as 
either spam or ham (not spam).

The goal of the project is to classify messages automatically and identify unwanted 
spam messages using natural language processing techniques.

## Dataset
The dataset used in this project contains two columns:

Category – Label of the message (spam or ham)  
Message – Text content of the SMS message

Example:
ham → normal message  
spam → promotional or unwanted message

## Technologies Used
Python  
NumPy  
Pandas  
Scikit-learn  
Google Colab  

## Project Workflow
1. Importing the dataset  
2. Data preprocessing  
3. Converting text data into numerical features  
4. Splitting the dataset into training and testing data  
5. Training the machine learning model  
6. Evaluating the model performance  

## Model Usage
The trained model can take a text message as input and predict whether the message 
is spam or not.

Example:
Input: "Congratulations! You have won a free ticket."  
Output: Spam

## How to Run the Project

1. Open the notebook in Google Colab

2. Upload the dataset file `mail_data.csv`

3. Run all cells in the notebook to train and test the model

## Project Structure

Spam-Mail-Detection
|
|-- spam_mail.ipynb
|-- mail_data.csv
|-- README.md

## Author
Harsh Mishra
