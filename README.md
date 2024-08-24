# Naive Bayes Sentiment Analysis Chatbot

## Overview
This project implements a chatbot equipped with sentiment analysis capabilities using a Naive Bayes classifier. The chatbot analyzes user input to determine whether the sentiment expressed is positive, negative, or neutral. This project combines natural language processing (NLP) techniques and machine learning algorithms to provide an interactive user experience.

## Features
- **Sentiment Analysis**: Classifies user messages as positive, negative, or neutral.
- **Natural Language Processing**: Utilizes text preprocessing techniques such as tokenization, stop word removal, and lemmatization.
- **Interactive Chatbot**: Engages users in conversation and provides sentiment feedback based on their input.

## Technologies Used
- **Python**: The primary programming language for the implementation.
- **scikit-learn**: For machine learning algorithms and model training.
- **NLTK**: For natural language processing tasks, including tokenization and lemmatization.
- **joblib**: For saving and loading trained models.
- **NumPy**: For numerical operations.

## Installation
To set up the project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/Prasanna-801/Sentiment-analysis-Chatbot.git
   cd naive-bayes-chatbot

   pip install -r requirements.txt

import nltk
nltk.download('punkt')
nltk.download('stopwords')
nltk.download('wordnet')

To run ---
# Activate the virtual environment
# For Windows
.\rasa_env\Scripts\activate

# For macOS/Linux
source rasa_env/bin/activate

# Run the scripts in order

python preprocessing_and_feature_extraction.py

python train_classifiers.py

python train_naive.py

python sentiment_analysis.py


Output --


Hello! How are you feeling today?

You: I am so happy!

Chatbot: Your sentiment is Positive.

You: This is terrible.

Chatbot: Your sentiment is Negative.

You: I feel okay.

Chatbot: Your sentiment is Neutral.

You: exit

Chatbot: Goodbye! Have a great day!
