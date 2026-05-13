# 🎫 Support Ticket Classification & Prioritization System

An end-to-end Machine Learning project that automatically classifies customer support tickets into categories and predicts their priority level using Natural Language Processing (NLP).

This project demonstrates practical ML skills used in real-world customer support systems, including text preprocessing, TF-IDF feature engineering, classification modeling, evaluation, and model serialization.

---

# 🚀 Project Overview

Companies receive thousands of support tickets every day through emails, chat systems, and helpdesk portals. Manually sorting these tickets is time-consuming and inefficient.

This project automates the process by:

* Classifying support tickets into categories
* Predicting ticket priority levels
* Reducing manual effort for support teams
* Improving response time for urgent issues
* Demonstrating practical NLP and Machine Learning workflows

---

# 🧠 Machine Learning Workflow

## 1. Data Collection

* Loaded customer support ticket dataset using Pandas
* Selected important columns:

  * Ticket Description
  * Ticket Type
  * Ticket Priority

## 2. Text Preprocessing

Performed NLP preprocessing steps:

* Lowercasing text
* Removing punctuation
* Removing stopwords
* Token cleaning

NLTK was used for natural language preprocessing.

## 3. Feature Engineering

Used **TF-IDF Vectorization** to convert ticket text into numerical features.

## 4. Model Training

Trained two separate Logistic Regression models:

| Model                         | Purpose                  |
| ----------------------------- | ------------------------ |
| Category Classification Model | Predicts ticket category |
| Priority Prediction Model     | Predicts urgency level   |

## 5. Model Evaluation

Evaluated models using:

* Accuracy Score
* Classification Report
* Confusion Matrix

## 6. Model Saving

Saved trained models using Joblib for future deployment.

---

# 🛠️ Technologies Used

| Technology           | Purpose                   |
| -------------------- | ------------------------- |
| Python               | Core Programming Language |
| Pandas               | Data Handling             |
| NumPy                | Numerical Operations      |
| NLTK                 | NLP Preprocessing         |
| Scikit-learn         | ML Models & Evaluation    |
| TF-IDF Vectorizer    | Text Feature Extraction   |
| Matplotlib / Seaborn | Data Visualization        |
| Joblib               | Model Serialization       |
| Jupyter Notebook     | Development Environment   |

---

# 📂 Project Structure

```bash
Support-Ticket-Classification/
│
├── Support_Ticket_Classification.ipynb
├── customer_support_tickets.csv
│
├── models/
│   ├── category_model.pkl
│   ├── priority_model.pkl
│   └── tfidf_vectorizer.pkl
│    
│
├── requirements.txt
└── README.md
```

---

# 📊 Model Pipeline

```text
Support Ticket
       ↓
Text Cleaning & Preprocessing
       ↓
TF-IDF Vectorization
       ↓
Machine Learning Models
       ↓
Category Prediction + Priority Prediction
```

---

# 📈 Sample Use Case

### Input Ticket

```text
My internet connection keeps disconnecting every few minutes and I cannot attend meetings.
```

### Predicted Output

| Prediction Type | Output            |
| --------------- | ----------------- |
| Ticket Category | Technical Support |
| Ticket Priority | High              |

---

# 💼 Business Impact

This system can help organizations:

* Improve customer support efficiency
* Automatically route tickets to correct departments
* Prioritize urgent issues faster
* Reduce response delays
* Enhance customer satisfaction
* Minimize manual workload

---

# 🔍 Key Features

✅ End-to-end NLP pipeline

✅ Real-world customer support use case

✅ Separate models for category and priority prediction

✅ TF-IDF based feature engineering

✅ Logistic Regression classification

✅ Model evaluation with confusion matrix

✅ Recruiter-friendly project structure

✅ Deployment-ready saved models

---

# 📥 Installation

## Clone Repository

```bash
git clone https://github.com/your-username/support-ticket-classification.git
cd support-ticket-classification
```

## Install Dependencies

```bash
pip install -r requirements.txt
```

## Run Notebook

```bash
jupyter notebook
```

---

# ▶️ Future Improvements

Possible future enhancements:

* Deep Learning using LSTM/BERT
* Streamlit Web Application Deployment
* Real-time ticket prediction API
* Multi-language support
* Automated ticket routing system
* Integration with helpdesk platforms

---

# 📌 Learning Outcomes

This project demonstrates understanding of:

* Natural Language Processing
* Text Classification
* Feature Engineering
* Supervised Machine Learning
* Model Evaluation
* Data Cleaning
* End-to-End ML Workflow
* Business-Oriented AI Solutions

---


# 📜 Conclusion

The Support Ticket Classification & Prioritization System is a practical NLP-based machine learning solution that automates customer support workflows. It demonstrates the ability to build real-world AI systems that improve operational efficiency and customer experience.

This project reflects strong foundational skills in:

* Machine Learning
* NLP
* Python Development
* Data Processing
* Business Problem Solving

---

# ⭐ If You Like This Project

Consider giving the repository a star and connecting for collaboration opportunities.
