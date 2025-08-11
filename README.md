# 📰 Fake News Prediction – Model Comparison

## 📌 Project Overview

This project aims to build and compare multiple machine learning models for **Fake News Detection**.  
The models are trained on the **Kaggle Fake News Dataset** and evaluated on standard metrics such as Accuracy, Precision, Recall, and F1-Score.


## 📂 Dataset

**Source:** [Kaggle Fake News Dataset](https://www.kaggle.com/c/fake-news/data)  
The dataset consists of:
- `train.csv` – Training data with labels (`0` = Real News, `1` = Fake News)  
- `test.csv` – Test data without labels  
- `submit.csv` – Sample submission format

**Columns in `train.csv`:**
- `id` → Unique article ID  
- `title` → Headline of the news article  
- `author` → Author of the article  
- `text` → Full news content  
- `label` → Target variable (`0` = Real, `1` = Fake)


## ⚙️ Models Implemented

The following models are trained and compared:
1. **Logistic Regression**
2. **Naive Bayes**
3. **Linear SVM**
4. **Random Forest**
5. **Gradient Boosting**
6. **XGBoost**


## 📊 Results Example

| Model               | Accuracy  | Precision | Recall   | F1 Score |
|---------------------|-----------|-----------|----------|----------|
| Logistic Regression | 0.979567  | 0.967259  | 0.992799 | 0.979863 |
| Naive Bayes         | 0.954808  | 0.993747  | 0.915506 | 0.953023 |
| Linear SVM          | 0.992788  | 0.993272  | 0.992319 | 0.992795 |
| Random Forest       | 0.993269  | 0.990922  | 0.995679 | 0.993295 |
| Gradient Boosting   | 0.964904  | 0.938037  | 0.995679 | 0.965999 |
| XGBoost             | 0.987500  | 0.981508  | 0.993759 | 0.987595 |

