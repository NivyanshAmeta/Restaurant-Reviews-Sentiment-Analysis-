# 🍽️ Restaurant Reviews Sentiment Analysis

This project focuses on performing **Natural Language Processing (NLP)** and **Sentiment Analysis** on restaurant review data to classify customer feedback as **positive** or **negative**.  
It demonstrates an end-to-end data analytics workflow — from **data cleaning** to **model training**, **evaluation**, and **visualization**.

---

## 📊 Project Overview

Customer reviews are a valuable source of insights for restaurants aiming to improve service quality and customer satisfaction.  
In this project, I built a machine-learning pipeline that automatically analyzes restaurant reviews and predicts sentiment using NLP techniques.

---

## 🧠 Objectives

- Clean and preprocess restaurant reviews data for analysis.  
- Transform text into numerical form for machine learning.  
- Train classification models to predict sentiment.  
- Evaluate model performance using appropriate metrics.  
- Visualize sentiment distribution and insights.  

---

## 🛠️ Tools & Technologies

| Category | Tools |
|-----------|--------|
| Programming | Python |
| Libraries | Pandas, NumPy, NLTK, Scikit-learn, Matplotlib, Seaborn |
| Analytics | SPSS (Regression & Predictive Validation) |
| Visualization | Power BI |
| Environment | Jupyter Notebook / VS Code |

---

## 🔍 Workflow

### 1. Data Cleaning
- Loaded raw restaurant reviews dataset (`reviews.csv`).
- Removed duplicates, null values, and special characters.
- Standardized text format (lowercasing, punctuation removal).

### 2. Text Preprocessing
- Tokenized sentences into words using **NLTK**.  
- Removed stopwords and applied **lemmatization**.  
- Created a clean, processed text corpus for modeling.

### 3. Text Vectorization
- Converted text to numerical features using **TF-IDF Vectorizer**.  
- Experimented with **Bag of Words (BoW)** representation for comparison.

### 4. Model Training
- Trained multiple classification models:
  - Logistic Regression  
  - Naïve Bayes  
  - Random Forest (for baseline comparison)
- Tuned hyperparameters using **GridSearchCV**.

### 5. Model Evaluation
- Evaluated models using:
  - Accuracy, Precision, Recall, F1-Score  
  - Confusion Matrix & ROC-AUC Curve
- Achieved an accuracy of **~88%** with Logistic Regression.

### 6. Statistical Validation (SPSS)
- Imported model predictions into **SPSS** for regression analysis and predictive validation.  
- Conducted univariate and bivariate testing to identify key factors driving positive sentiment.

### 7. Visualization
- Built a **Power BI dashboard** to visualize:
  - Sentiment distribution by restaurant category  
  - Average ratings vs. sentiment polarity  
  - Common positive and negative keywords (Word Cloud)

---

## 📈 Results & Insights

- Identified top service-related keywords influencing customer satisfaction.  
- Found that **service speed** and **food quality** had the highest correlation with positive reviews.  
- Provided actionable insights for restaurant management teams to enhance customer experience.

---

## 📂 Repository Structure

