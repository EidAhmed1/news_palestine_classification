# 📰 Palestine News Classification System

An end-to-end Machine Learning project for classifying Palestinian news articles using Natural Language Processing (NLP) techniques and multiple classification algorithms.

---

## 🧠 Project Overview

This project focuses on building a complete **Machine Learning pipeline** for text classification.  
It processes news articles, extracts meaningful features using NLP techniques, and applies multiple ML models to predict the correct category of each news article.

The system is designed for experimentation, model comparison, and performance optimization.

---

## 🚀 Features

- 🧹 Advanced text preprocessing using Regex
- 🧠 NLP feature extraction using TF-IDF
- 🤖 Multiple Machine Learning models:
  - Logistic Regression
  - Random Forest
  - XGBoost
- ⚙️ End-to-end ML Pipeline using Scikit-learn
- 🔍 Hyperparameter tuning using GridSearchCV
- 📊 Model evaluation using:
  - Accuracy Score
  - Confusion Matrix
  - Classification Report
- 📈 Learning curve analysis
- 🔄 Model comparison and selection

---

## 🏗️ Workflow

1. Load dataset using Pandas  
2. Clean and preprocess text data using Regex  
3. Convert text into numerical features using TF-IDF  
4. Split data into training and testing sets  
5. Train multiple machine learning models  
6. Optimize models using GridSearchCV  
7. Evaluate performance using multiple metrics  
8. Compare results and select the best model  

---

## 🤖 Machine Learning Models

| Model | Description |
|------|-------------|
| Logistic Regression | Strong baseline linear classifier for text data |
| Random Forest | Ensemble learning model for improved robustness |
| XGBoost | Gradient boosting model for high performance |

---

## 📊 Evaluation Metrics

- Accuracy Score  
- Precision, Recall, F1-score  
- Confusion Matrix  
- Learning Curves  

---

## 🛠️ Tech Stack

- Python 🐍  
- Pandas & NumPy  
- Scikit-learn 🤖  
- XGBoost ⚡  
- Matplotlib 📊  
- NLP (TF-IDF, Regex)  

---

## 📦 Installation

```bash
git clone https://github.com/EidAhmed1/news_palestine_classification.git
cd news_palestine_classification
pip install -r requirements.txt
