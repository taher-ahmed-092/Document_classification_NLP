# US Economy Document Classification (NLP)

## 📌 Project Overview
This project focuses on **binary text classification** – determining whether an article is **relevant to the US economy or not**.  

The dataset was sourced from **Kaggle** and is **imbalanced**, which impacted model performance and scores. Despite this, the workflow demonstrates key **NLP techniques, feature engineering, pipeline optimization, and model deployment readiness**.

---

## 🎯 Objectives
- Classify articles into **US Economy Relevant** vs **Not Relevant**.  
- Build and evaluate multiple ML models.  
- Handle text preprocessing, feature extraction, and efficiency improvements.  
- Save trained models for deployment.  

---

## 🗂️ Dataset
- **Source**: Kaggle  
- **Type**: Text articles  
- **Target Variable**: Binary (Relevant / Not Relevant)  
- ⚠️ **Note**: Dataset is **imbalanced**, which limits accuracy scores.  

---

## ⚙️ Workflow & Methodology
1. **Data Exploration**
   - Generated **WordClouds** to visualize text patterns.  
   - Plotted **confusion matrices** to analyze classification results.  

2. **Preprocessing**
   - Implemented a custom `clean()` function for text cleaning.  
   - Used **TF-IDF Vectorizer** for feature extraction.  

3. **Pipeline & Optimization**
   - Created reusable **pipelines** for preprocessing and model training.  
   - Implemented **caching and memoization** to improve runtime efficiency.  
   - Optimized models using **GridSearchCV** for hyperparameter tuning.  

4. **Models Implemented**
   - Logistic Regression  
   - Naive Bayes  
   - Decision Tree  
   - Multinomial Naive Bayes (Demo Model)  

5. **Deployment Readiness**
   - Trained models are saved as `.pkl` files:
     - `logistic_regression.pkl`  
     - `demo_model_nb.pkl`  
     - `decision_tree.pkl`  
     - `naive_bayes.pkl`  

---

## 📊 Results
- Models achieved **moderate performance** due to **dataset imbalance**.  
- Evaluation used **confusion matrices, classification metrics and f1 score**.  

---

## 👤 Author
**Taher Ahmed**  
🔗 [GitHub Profile](https://github.com/taher-ahmed-092)  
