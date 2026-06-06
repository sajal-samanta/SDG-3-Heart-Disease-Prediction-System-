# ❤️ Heart Disease Prediction System – Supporting SDG 3

![SDG 3](https://img.shields.io/badge/SDG-3%20Good%20Health%20%26%20Well--being-27AE60)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Random%20Forest-blue)
![Streamlit](https://img.shields.io/badge/Web%20App-Streamlit-red)

## 🌍 Aligned with UN Sustainable Development Goal 3

> **SDG Target 3.4:** By 2030, reduce by one third premature mortality from non-communicable diseases (NCDs) through prevention and treatment.

Cardiovascular diseases (CVDs) are the **leading cause of death globally**, accounting for an estimated **17.9 million deaths annually** (WHO). Many of these deaths are preventable with early detection and lifestyle changes.

This project contributes directly to SDG 3 by providing a **free, accessible, and easy-to-use** machine learning tool that predicts heart disease risk using basic clinical parameters. It empowers individuals and community health workers to identify at-risk people early – before a major cardiac event occurs.

---

## 📋 Table of Contents

- [About the Project](#about-the-project)
- [How It Supports SDG 3](#how-it-supports-sdg-3)
- [Key Features](#key-features)
- [Technology Stack](#technology-stack)
- [Dataset](#dataset)
- [Model Performance](#model-performance)
- [Installation & Usage](#installation--usage)
- [Screenshots](#screenshots)
- [Future Work](#future-work)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## 📌 About the Project

This is an end‑to‑end **Heart Disease Risk Prediction System** built with machine learning. Users input 13 clinical parameters (age, cholesterol, blood pressure, etc.) and the system returns a **low/high risk** prediction with 86.9% accuracy. The web interface is built with **Streamlit**, making it intuitive for non‑technical users.

The goal is to democratize heart health screening – especially in underserved communities where access to cardiologists is limited.

---

## 🎯 How It Supports SDG 3

| SDG 3 Target | How This Project Helps |
|--------------|------------------------|
| **3.4** – Reduce NCD mortality | Enables early detection of heart disease risk, allowing timely medical or lifestyle intervention. |
| **3.8** – Universal health coverage | Provides free, low‑tech screening that can be deployed in rural clinics without expensive equipment. |
| **3.d** – Improve early warning systems | Acts as a digital risk‑assessment tool that complements traditional healthcare. |

In addition, the project:
- ✅ Encourages preventive healthcare
- ✅ Increases awareness of cardiovascular health
- ✅ Supports informed medical decisions
- ✅ Promotes healthy lifestyle choices

---

## ✨ Key Features

- **🔮 Accurate Prediction** – Random Forest model with 86.9% accuracy
- **📊 Real-time Visualizations** – Interactive charts (Plotly, Matplotlib)
- **⚠️ Risk Categorization** – Clear low/high risk output with confidence
- **📜 Historical Tracking** – Stores past predictions (SQLite)
- **🧠 Explainable AI** – Shows feature importance & model insights
- **🌍 SDG Alignment** – Explicitly linked to UN SDG 3 throughout the UI

---

## ⚙️ Technology Stack

| Area | Technologies |
|------|--------------|
| **Machine Learning** | Scikit-learn, Random Forest, XGBoost, Logistic Regression, SVM |
| **Data Processing** | Pandas, NumPy |
| **Web Framework** | Streamlit |
| **Visualization** | Plotly, Matplotlib, Seaborn |
| **Database** | SQLite, Joblib |

---

## 📊 Dataset

- **Source:** UCI Heart Disease dataset (or your actual source)
- **Records:** 303 patients
- **Features:** 13 clinical parameters (age, sex, chest pain type, resting BP, cholesterol, fasting blood sugar, resting ECG, max heart rate, exercise induced angina, ST depression, slope, number of major vessels, thal)
- **Target:** Binary classification (presence or absence of heart disease)

---

## 📈 Model Performance

| Metric | Score |
|--------|-------|
| Accuracy | 86.9% |
| AUC Score | 0.921 |
| Precision | 87% |
| Recall | 86% |

The **Random Forest** classifier outperformed other models (XGBoost, Logistic Regression, SVM) on this dataset.

---

## 🚀 Installation & Usage

### Prerequisites
- Python 3.8+
- Git

### Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/sajal-samanta/heart-disease-prediction-sdg3.git
   cd heart-disease-prediction-sdg3



   🙏 Acknowledgments

   
World Health Organization (WHO) for SDG 3 data and statistics

UCI Machine Learning Repository for the heart disease dataset

Streamlit for the amazing web framework

*This project was developed as part of an ESD (Engineering for Sustainable Development) submission to demonstrate how machine learning can directly contribute to SDG 3 – Good Health and Well-being.*



cd heart-disease-prediction

python -m streamlit run app.py
