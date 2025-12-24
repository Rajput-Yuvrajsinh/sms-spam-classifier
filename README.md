📧 Email / SMS Spam Classifier using Python & Streamlit

📌 Project Overview

This project is a Machine Learning–based Email/SMS Spam Classifier that predicts whether a given message is Spam or Not Spam (Ham).
It uses Natural Language Processing (NLP) techniques and a Naive Bayes classifier, deployed through a Streamlit web application.

🎯 Problem Statement
Spam messages are a common problem that waste time and may lead to fraud.
The objective of this project is to automatically classify incoming messages as spam or legitimate using machine learning.

🧠 Machine Learning Approach
Text Preprocessing using NLP
TF-IDF Vectorization
Multinomial Naive Bayes Classifier
Model Serialization using Pickle
Interactive UI using Streamlit

📂 Dataset
Dataset Name: Spam SMS Dataset
Source: UCI Machine Learning Repository
Columns Used:
v1 → Label (ham, spam)
v2 → Message text

⚙️ Technologies Used
Python
Pandas
Scikit-learn
NLTK
Streamlit
Pickle

🔍 Text Preprocessing Steps
Convert text to lowercase
Tokenization
Remove non-alphanumeric characters
Remove stopwords and punctuation
Apply stemming using Porter Stemmer

🧪 Model Used
Multinomial Naive Bayes
Well-suited for text classification problems
Efficient and fast for large datasets

📊 Feature Extractio
TF-IDF Vectorizer
Maximum features: 3000
Converts text into numerical vectors

🚀 Application Features
User-friendly web interface
Real-time spam prediction

Clear result display:
❌ Spam
✅ Not Spam

📈 Model Output
Spam → Displayed in red
Not Spam → Displayed in green

🧪 Example
Input:
"Congratulations! You have won a free prize"
Output:
❌ Spam

🔮 Future Enhancements
Improve accuracy using advanced models (Logistic Regression, SVM)
Add model performance metrics
Deploy on cloud (Heroku / Streamlit Cloud)
Support multiple languages

🧠 Learning Outcomes
Hands-on NLP preprocessing
TF-IDF vectorization
Naive Bayes implementation
Model deployment using Streamlit
End-to-end ML project workflow
