# 📊 Customer Churn Prediction using Machine Learning

This project predicts whether a customer is **likely to stay** or **leave (churn)** a company using Machine Learning. It uses the **IBM Telco Customer Churn** dataset to train and test different classification models.

---

# 📌 Project Overview

The main goal of this project is to predict customer churn.

Customer churn means a customer stops using a company's service.

This project helps companies identify customers who may leave so they can improve customer retention.

---
# Notes:
Churn means a customer stops using the company's service or leaves the company.

Tenure means the number of months a customer has been using the company's service.
Churn Distribution – Shows how many customers stayed and how many left the company.
Tenure vs Churn – Shows how the number of months a customer has used the service affects churn.
Monthly Charges vs Churn – Shows whether monthly subscription charges affect customer churn.
Contract Type vs Churn – Shows which contract types have more customers leaving the company.
Correlation Between Features – Shows how different customer features are related to each other.

# 🎯 Project Objectives

- Load the customer dataset.
- Clean and preprocess the data.
- Analyze the data using EDA.
- Create charts and graphs.
- Train different Machine Learning models.
- Compare model performance.
- Predict whether a customer will stay or churn.

---

# 📂 Dataset

**Dataset Name**

IBM Telco Customer Churn Dataset

**File**

```
WA_Fn-UseC_-Telco-Customer-Churn.csv
```

### Dataset contains

- Customer ID
- Gender
- Senior Citizen
- Partner
- Dependents
- Tenure
- Phone Service
- Multiple Lines
- Internet Service
- Online Security
- Online Backup
- Device Protection
- Tech Support
- Streaming TV
- Streaming Movies
- Contract
- Paperless Billing
- Payment Method
- Monthly Charges
- Total Charges
- Churn (Target Column)

---

# 🛠️ Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost (Optional)

---

# 📊 Data Analysis (EDA)

The following analysis was performed:

- Churn Distribution
- Tenure vs Churn
- Monthly Charges vs Churn
- Contract Type vs Churn
- Correlation Between Features

---

# 📈 Data Visualizations

The project includes:

- Churn Distribution Pie Chart
- Contract Type Bar Chart
- Correlation Heatmap
- Monthly Charges Histogram
- Tenure vs Churn Box Plot
- Monthly Charges vs Churn Box Plot

---

# 🤖 Machine Learning Models

The following models were used:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- XGBoost (Optional)

---

# 📋 Model Evaluation

The models were evaluated using:

- Accuracy Score
- Precision
- Recall
- F1 Score
- Confusion Matrix

---

# 💻 Prediction System

A simple console-based prediction system is included.

The user enters customer details, and the model predicts whether the customer is:

- ✅ Customer Likely to Stay

or

- ❌ Customer Likely to Churn

---

# ⚠️ Error Handling

The system checks for:

- Invalid inputs
- Wrong data types
- Runtime errors

It displays helpful error messages if the user enters incorrect values.

---

# 📁 Project Structure

```
Customer_Churn_Prediction_ML/
│
├── WA_Fn-UseC_-Telco-Customer-Churn.csv
├── Customer_Churn_Prediction.ipynb
├── customer_churn_model.pkl
├── README.md
└── requirements.txt
```

---

# ▶️ How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/Customer_Churn_Prediction_ML.git
```

### 2. Open the Project Folder

```bash
cd Customer_Churn_Prediction_ML
```

### 3. Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost
```

### 4. Run the Project

Open the notebook in **Google Colab** or **Jupyter Notebook** and run all cells.

---

# 📌 Project Workflow

```
Load Dataset
      ↓
Data Validation
      ↓
Data Preprocessing
      ↓
Exploratory Data Analysis (EDA)
      ↓
Data Visualization
      ↓
Train Machine Learning Models
      ↓
Evaluate Models
      ↓
Customer Churn Prediction
```

---

# 📷 Sample Output

```
==================================================
      CUSTOMER CHURN PREDICTION SYSTEM
==================================================

Prediction Result
------------------------------
Customer Likely to Stay
```

or

```
==================================================
      CUSTOMER CHURN PREDICTION SYSTEM
==================================================

Prediction Result
------------------------------
Customer Likely to Churn
```

---

# 📚 What I Learned

- Data Cleaning
- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Data Visualization
- Feature Encoding
- Machine Learning Classification
- Model Evaluation
- Customer Churn Prediction

---

# 👨‍💻 Author

**Maheesh Varma Ugge**

Machine Learning Internship Project
