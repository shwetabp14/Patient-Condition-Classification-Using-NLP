# Patient-Condition-Classification-Using-NLP


This project is an NLP-based Machine Learning system that predicts a patient's medical condition using patient drug reviews.

---

## 📌 Project Overview
Patient reviews often contain useful information about symptoms, experience, and outcomes.  
In this project, I built a text classification model using NLP techniques to predict the **condition category** from the given review.

---

## 📂 Files in this Repository
- `Drugs_review.ipynb` → Data preprocessing, EDA, NLP cleaning, model building & evaluation
- `drug_app.ipynb` → Prediction/testing notebook (and app logic if included)
- `drugsCom_raw.xlsx` → Dataset used in the project
- `README.md` → Project documentation

---

##  Tech Stack Used
- Python
- Pandas, NumPy
- NLTK / Regex text cleaning
- Scikit-learn
- TF-IDF Vectorizer
- Machine Learning Models (Logistic Regression / Naive Bayes etc.)

---

##  ML Workflow
1. Load dataset (`drugsCom_raw.xlsx`)
2. Data Cleaning & Preprocessing
3. Text preprocessing (stopwords removal, lemmatization, etc.)
4. Feature extraction using TF-IDF
5. Model training & evaluation
6. Predict condition from new input text

---

##  Model Evaluation
Model performance is evaluated using:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

---

##  How to Run
1. Clone the repository
```bash
git clone https://github.com/your-username/Patient-Condition-Classification-Using-NLP.git
cd Patient-Condition-Classification-Using-NLP
---
2. Open the notebooks in Jupyter / VS Code
- Run `Drugs_review.ipynb` first
- Then run `drug_app.ipynb`


