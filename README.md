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
