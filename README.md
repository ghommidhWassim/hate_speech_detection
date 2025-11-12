# hate_speech_detection
🧠 Abusive Language Detection (Hate Speech Classification)
📌 Project Description

This project aims to build a machine learning model that automatically detects abusive, offensive, or hateful language in social media posts (tweets, comments, etc.).

The approach is based on a text processing and classification pipeline combining linguistic cleaning, feature extraction, and supervised learning using a Decision Tree Classifier.

⚙️ Pipeline Overview

Data Collection & Preparation

Text data collected from social media platforms.

Cleaning includes removing URLs, punctuation, numbers, and irrelevant emojis.

Text Preprocessing (NLP)

Convert all text to lowercase.

Remove stopwords (e.g., “the”, “is”, “and”).

Apply stemming to reduce words to their root form.

Tokenize the text into individual words.

Vectorization

Convert text into numeric features using TF-IDF or CountVectorizer.

Model Training

Model: DecisionTreeClassifier (scikit-learn)

Dataset split: 67% training / 33% testing

Model Evaluation

Accuracy: 0.875

Log Loss: 4.42

Error Rate: 0.125

Classification Report:

Class	Precision	Recall	F1-Score
Hate Speech Detected	0.38	0.35	0.36
No Hate / Non-Offensive	0.80	0.83	0.81
Offensive Language	0.93	0.92	0.93
Overall Accuracy	0.88		
