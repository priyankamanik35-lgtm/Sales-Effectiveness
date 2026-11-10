# 📊 Sales Effectiveness Prediction

## 🚀 Project Overview

Businesses generate thousands of sales leads from multiple marketing channels, but not every lead converts into a customer. Identifying high-potential leads helps sales teams focus their efforts, improve conversion rates, and optimize resources.

This project leverages Machine Learning to predict the effectiveness of sales leads based on customer and campaign-related attributes. The solution performs comprehensive data analysis, feature engineering, model building, and lead classification to support data-driven sales decisions.

---

## 🎯 Business Problem

Sales teams often spend significant time pursuing leads that may never convert. Without a systematic lead scoring mechanism:

- Sales productivity decreases
- Conversion rates remain low
- Resources are wasted on low-quality leads
- Revenue opportunities are missed

The objective of this project is to develop a predictive model that can identify potential leads and improve sales effectiveness.

---

## 🛠️ Project Workflow

### 1. Data Understanding
- Analyze lead attributes and business context
- Understand target variable distribution
- Explore categorical and numerical features

### 2. Data Preprocessing
- Missing value treatment
- Duplicate record handling
- Outlier analysis
- Feature encoding
- Data transformation

### 3. Exploratory Data Analysis (EDA)
- Lead source analysis
- Customer behavior analysis
- Correlation analysis
- Conversion trend visualization
- Feature impact assessment

### 4. Feature Engineering
- Creation of meaningful predictors
- Encoding categorical variables
- Feature selection

### 5. Model Building
- Train-test split
- Model training
- Hyperparameter tuning
- Performance evaluation

### 6. Lead Effectiveness Prediction
- Predict lead conversion potential
- Classify leads into effective/non-effective categories
- Support sales prioritization

---

## 📂 Repository Structure

```text
Sales-Effectiveness/
│
├── Sales_effectiveness_Analysis.ipynb
├── sales_data.csv
├── sales_lead_model.joblib
└── README.md
```

| File | Description |
|--------|------------|
| Sales_effectiveness_Analysis.ipynb | Complete EDA, preprocessing, model building, and evaluation |
| sales_data.csv | Dataset used for training and analysis |
| sales_lead_model.joblib | Saved machine learning model |
| README.md | Project documentation |

---

## 📊 Technologies Used

### Programming Language
- Python

### Libraries
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib

### Development Environment
- Jupyter Notebook

---

## 🔍 Exploratory Data Analysis

Key analyses performed include:

✅ Lead source distribution

✅ Conversion analysis

✅ Feature relationship visualization

✅ Numerical feature distributions

✅ Business insight extraction

✅ Correlation assessment

---

## 🤖 Machine Learning Pipeline

The ML workflow includes:

```text
Raw Data
    ↓
Data Cleaning
    ↓
Feature Engineering
    ↓
Data Encoding
    ↓
Model Training
    ↓
Model Evaluation
    ↓
Lead Effectiveness Prediction
```

---

## 📈 Model Evaluation

Models are evaluated using:

- Accuracy Score
- Precision
- Recall
- F1 Score
- Confusion Matrix
- Classification Report

The best-performing model is saved as:

```python
sales_lead_model.joblib
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/priyankamanik35-lgtm/Sales-Effectiveness.git
```

```bash
cd Sales-Effectiveness
```

### Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn joblib
```

---

## ▶️ Run the Project

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
Sales_effectiveness_Analysis.ipynb
```

---

## 🧪 Using the Saved Model

```python
import joblib

model = joblib.load('sales_lead_model.joblib')

prediction = model.predict(new_data)

print(prediction)
```

---

## 📌 Business Impact

This solution helps organizations:

- Prioritize high-quality leads
- Improve sales efficiency
- Reduce effort on non-promising prospects
- Increase conversion opportunities
- Support strategic decision-making

---

## 🚀 Future Enhancements

- Streamlit web application deployment
- Automated lead scoring system
- Real-time prediction API
- Model monitoring dashboard
- Power BI integration

---

## 👨‍💻 Author

**Priyanka Manik**

GitHub: https://github.com/priyankamanik35-lgtm

---



