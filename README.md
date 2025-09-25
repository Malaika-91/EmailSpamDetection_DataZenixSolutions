# EmailSpamDetection_DataZenixSolutions
📧 Spam Detection using Naive Bayes

This project implements a Spam Message Classifier using TF-IDF Vectorization and Multinomial Naive Bayes (NB).
It classifies SMS messages as either Spam or Ham (Not Spam) with high accuracy.

🚀 Project Overview

Loads the SMS Spam Collection Dataset (spam.csv).

Cleans and prepares the dataset by selecting relevant columns.

Encodes the labels (ham = 0, spam = 1).

Splits the dataset into training and testing sets.

Converts text into numeric features using TfidfVectorizer.

Trains a Naive Bayes classifier on the training data.

Evaluates performance using accuracy score and classification report.

Includes a custom predict function for new messages.

🛠️ Technologies Used

Python 3.x

Pandas (for dataset handling)

Scikit-learn (for ML model, vectorization, and evaluation)

📂 Dataset

File: spam.csv

Columns used:

v1 → Label (ham or spam)

v2 → Message text

📌 Steps in Code

Import libraries

Load and clean dataset

Split into training and testing sets

Vectorize messages using TF-IDF

Train Naive Bayes model

Evaluate with accuracy and classification report

Predict new unseen messages

📊 Model Performance

The trained model achieves high accuracy in spam detection:

Accuracy: ~97–99% (depends on split)

Classification Report: Shows precision, recall, and F1-score for both ham and spam.

🔍 Example Predictions
print(predict("Congratulations! You won a cash prize"))
# Output: Spam

print(predict("Hi, how are you? Can we meet tomorrow"))
# Output: ham

▶️ How to Run

Clone or download this repository.

Install dependencies:

pip install pandas scikit-learn


Run the script:

python spam_detection.py

📌 Learning Outcomes

How to preprocess text data.

How to use TF-IDF vectorization for feature extraction.

Training and evaluating a Naive Bayes classifier.

Building a custom prediction function for new inputs.

✨ This project demonstrates how simple ML techniques can effectively solve real-world problems like spam detection.
