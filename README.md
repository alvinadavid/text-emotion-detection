# text-emotion-detection
Text emotion detection

# Problem Statement 
In today’s digital world, people express emotions through text on platforms like social media, emails, and chats. Understanding the emotion behind a large amount of text manually is time-consuming and difficult. There is a need for an automated system that can detect and classify emotions from text to help understand user sentiment and behavior effectively.

# Solution
This project is a web application built using Python, NLP, and Streamlit that can identify emotions such as joy, sadness, anger, fear, neutral, and shame from user-input text.
The text data is cleaned using neattext, transformed into numerical features using CountVectorizer, and passed through trained machine learning models like Logistic Regression, SVM, and Random Forest.
The best-performing model is deployed in a Streamlit interface, which displays both the predicted emotion and a probability chart for better understanding. The model is saved using joblib for quick and reliable predictions.

# Tech Stack
Tech Stack: Python, Streamlit, scikit-learn, pandas, numpy, pickle



# Prediction: Positive
# <img width="1012" height="826" alt="text detect +" src="https://github.com/user-attachments/assets/131ae350-069e-4890-9659-21e964e9bdee" />

# Prediction: Negative
# <img width="1025" height="838" alt="text detect -" src="https://github.com/user-attachments/assets/34975631-1910-4e1b-8fef-fda1c98668af" />



