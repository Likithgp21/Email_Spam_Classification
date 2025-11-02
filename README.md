**Email Spam Classification System**

**Overview**
The Email Spam Classification System uses machine learning techniques to classify emails as either "ham" (non-spam) or "spam." The system leverages TF-IDF Vectorizer for feature extraction, Logistic Regression for classification, and a pickled model for efficient spam detection. The application is built using Flask, offering a simple interface for real-time spam classification.
________________________________________
**Features**
1.	Spam Detection: Automatically classifies incoming emails as "spam" or "ham" (non-spam).
2.	TF-IDF Vectorization: Extracts text features such as keywords, patterns, and phrases from email content for accurate classification.
3.	Logistic Regression: A robust machine learning model used for predicting whether an email is spam based on its features.
4.	Flask Web Application: A lightweight backend application that accepts email text as input and returns its classification in real-time.
________________________________________
**Purpose**
The system aims to help users filter out unwanted emails, improving productivity and preventing phishing, scams, and other malicious activities. By using advanced machine learning techniques, the system classifies emails based on text patterns, keyword frequency, and metadata like the sender’s information, ensuring efficient spam detection.
________________________________________
**Technical Requirements**
1.	Python 3.6 or higher
2.	Flask: Web framework for building the application
3.	scikit-learn: For machine learning models
4.	pickle: For saving and loading the trained model
5.	nltk / stopwords: For text preprocessing and tokenization
6.	pandas and numpy: For data handling and processing

