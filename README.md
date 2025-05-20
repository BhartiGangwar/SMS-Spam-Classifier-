# SMS-Spam-Classifier-
# 📩 SMS Spam Classifier

This is a machine learning-based web app that classifies SMS messages as **Spam** or **Not Spam** using Natural Language Processing (NLP) techniques. The model is built using `scikit-learn` and deployed with `Streamlit` for real-time spam detection.

![App Screenshot](screenshot.png) <!-- Optional: Replace with your own screenshot -->

---

## 🔍 Problem Statement

Spam messages are a common nuisance. The goal of this project is to automatically classify whether an incoming message is spam or not using NLP and machine learning techniques.

---

## 🚀 Tech Stack

- **Python**
- **scikit-learn**
- **NLP (Text Preprocessing, TF-IDF)**
- **Streamlit** (for deployment)

---

## 📁 Project Structure

SMS-Spam-Classifier/
├── app.py # Streamlit app
├── spam.csv # Dataset
├── model.pkl # Trained ML model
├── vectorizer.pkl # TF-IDF vectorizer
└── README.md # Project documentation

yaml
Copy
Edit

---

## 🧠 Features

- Clean and preprocess SMS data (stopword removal, stemming, etc.)
- Convert text to vectors using **TF-IDF**
- Train multiple models: Naive Bayes, Logistic Regression, etc.
- Naive Bayes gives best results with **97% accuracy** and **1.0 precision**
- Real-time classification using Streamlit UI

