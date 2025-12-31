# 🧠 Sentiment Analysis with NLP using TF-IDF and Logistic Regression

## 📌 Project Overview
This project performs **sentiment analysis on customer reviews** using **Natural Language Processing (NLP)** techniques.  
The goal is to classify customer reviews as **Positive** or **Negative** using **TF-IDF vectorization** and **Logistic Regression**.

This project demonstrates a complete NLP pipeline including preprocessing, feature extraction, model training, and evaluation.

---

## 🎯 Objective
- Preprocess raw text data
- Convert text into numerical features using TF-IDF
- Train a Logistic Regression classifier
- Evaluate sentiment prediction performance
- Test the model on new, unseen reviews

---

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- NLTK
- Scikit-learn
- Jupyter Notebook

---

## 📊 Dataset
- **Customer Reviews Dataset**
- Two columns:
  - `review` → Customer review text
  - `sentiment` → Sentiment label  
    - `1` = Positive  
    - `0` = Negative

The dataset is balanced to avoid model bias.

---

## 🔍 Project Workflow
1. Import required libraries
2. Load customer reviews dataset
3. Text preprocessing:
   - Lowercasing
   - Removing punctuation
   - Removing stopwords
   - Stemming
4. Feature extraction using TF-IDF
5. Train-test split
6. Model training using Logistic Regression
7. Model evaluation using accuracy and classification report
8. Prediction on sample customer reviews

---

## ⚙️ Model Used
- **Logistic Regression**
- TF-IDF vectorization with a limited number of features
- Balanced class weights to handle small dataset size

---

## 📈 Results
- The model successfully learned sentiment patterns from text data
- Accuracy and classification metrics were generated
- Sample predictions demonstrate sentiment classification on unseen reviews

Example:
I love this product → Positive
This is the worst purchase ever → Negative
