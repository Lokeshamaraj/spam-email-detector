# Spam Email Detection using Machine Learning

##  About the Project

This project is a simple Machine Learning model that classifies SMS messages as **Spam** or **Not Spam (Ham)**.

I built this project as part of my learning in AI/ML to understand how text data can be processed and used for prediction.

---

##  Objective

The main goal of this project is to detect whether a message is spam or not using Natural Language Processing (NLP) and Machine Learning.

---

##  Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Jupyter Notebook

---

##  How It Works

1. Load the dataset of SMS messages
2. Clean the text (lowercase, remove punctuation, etc.)
3. Convert text into numbers using **TF-IDF**
4. Train a **Naive Bayes model**
5. Predict whether a message is Spam or Not Spam

---

##  Model Performance

* Accuracy: ~95%
* The model performs well on most messages but may misclassify some edge cases.

---

##  Example
Input:
"Win ₹5000 now!!!"
Output:
Spam

Input:
"Hey, how are you?"
Output:
Not Spam

---

## Project Structure

* dataset/ → contains the dataset
* notebook/ → Jupyter Notebook with code
* model/ → saved ML model and TF-IDF
* README.md → project description

---

##  Future Improvements

* Try other models like Logistic Regression
* Improve text preprocessing
* Handle class imbalance
* Build a simple web app using Streamlit

---

##  What I Learned

* Basics of NLP (text cleaning, TF-IDF)
* How Machine Learning models work
* Model training and evaluation
* Using Git and GitHub for projects

---


