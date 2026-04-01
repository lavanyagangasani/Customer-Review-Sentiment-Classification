# 📊 Customer Review Sentiment Classification

## 📌 Project Overview

This project focuses on analyzing customer reviews and classifying them into **Positive**, **Negative**, and **Neutral** sentiments using Natural Language Processing (NLP) techniques. It transforms unstructured textual data into meaningful insights that help understand customer opinions.

---

## 🎯 Objective

* To preprocess raw customer review data
* To extract important textual features using TF-IDF
* To analyze sentiment using lexicon-based methods
* To visualize sentiment patterns effectively

---

## 🧠 Technologies Used

* Python
* Google Colab
* NLP (NLTK)
* Scikit-learn
* Pandas & NumPy
* Matplotlib & Seaborn
* WordCloud

---

## 📂 Dataset

This project uses the **Amazon Fine Food Reviews Dataset**, which contains real customer reviews along with rating scores.

* The dataset includes:

  * Review Text
  * Review Score (1–5)
* Sentiment labels are derived from the score:

  * Positive → Score > 3
  * Neutral → Score = 3
  * Negative → Score < 3

🔗 Dataset Link:
https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews

---

## ⚙️ Project Workflow

### 1️⃣ Data Loading

* Dataset is loaded into Google Colab
* Required fields are extracted for analysis

---

### 2️⃣ Data Preprocessing

* Convert text to lowercase
* Remove punctuation and special characters
* Tokenization
* Stopword removal

---

### 3️⃣ Feature Extraction

* TF-IDF Vectorization
* N-gram (Bigram) modeling to capture context

---

### 4️⃣ Sentiment Analysis

* Lexicon-based sentiment scoring using VADER
* Generates polarity scores ranging from -1 to +1

---

### 5️⃣ Sentiment Classification

* Convert sentiment scores into categories:

  * Positive
  * Negative
  * Neutral

---

### 6️⃣ Data Visualization

* Sentiment distribution using bar charts
* Proportion analysis using pie charts
* WordCloud for frequent terms

---

## 📊 Results

* Successfully classified customer reviews into sentiment categories
* Identified key patterns in customer opinions
* Generated visual insights for better interpretation

---

## 🚀 How to Run the Project

1. Open Google Colab
2. Install required libraries
3. Load dataset using KaggleHub or CSV
4. Execute all cells step-by-step
5. Analyze outputs and visualizations

---

## 📌 Key Features

✔ Text preprocessing pipeline
✔ TF-IDF with N-grams
✔ Lexicon-based sentiment scoring
✔ Data visualization
✔ Real-world dataset analysis

---

## 🧠 Future Improvements

* Apply Machine Learning models for higher accuracy
* Build a web-based dashboard
* Use deep learning techniques for advanced analysis

---

## 🙌 Conclusion

This project demonstrates how customer reviews can be processed and analyzed using NLP techniques to extract valuable insights and support data-driven decision-making.

---
