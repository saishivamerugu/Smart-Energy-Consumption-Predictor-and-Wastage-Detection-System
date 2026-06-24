# ⚡ Smart Energy Consumption Predictor & Wastage Detection System

A Machine Learning-based web application that predicts electricity consumption, detects potential energy wastage, and provides data-driven insights for energy optimization. The system leverages historical energy usage data to forecast future consumption patterns and identify abnormal energy usage that may indicate wastage.

## 🚀 Live Demo

🌐 **Application URL:**
[https://crop-patience-appetizer.ngrok-free.dev/](https://crop-patience-appetizer.ngrok-free.dev/)

---

## 📌 Project Overview

Energy consumption management plays a critical role in reducing operational costs and promoting sustainability. This project utilizes Machine Learning techniques to analyze historical energy usage data, forecast future consumption, and detect unusual energy usage patterns that may lead to unnecessary energy wastage.

The application provides interactive visualizations and predictive analytics through a user-friendly Streamlit interface.

---

## ✨ Features

* 📊 Historical Energy Consumption Analysis
* 🔮 Future Energy Consumption Prediction
* ⚡ Energy Wastage Detection
* 📈 Interactive Data Visualizations
* 🤖 Multiple Machine Learning Models Comparison
* 📉 Consumption Trend Analysis
* 🎯 Real-Time Prediction Interface
* 📋 Energy Efficiency Insights

---

## 🛠️ Tech Stack

### Programming Language

* Python

### Libraries & Frameworks

* Pandas
* NumPy
* Scikit-Learn
* XGBoost
* Matplotlib
* Streamlit

### Machine Learning Models

* Linear Regression
* Random Forest Regressor
* XGBoost Regressor

---

## 📂 Project Structure

```bash
Smart-Energy-Consumption-Predictor/
│
├── data/
│   └── energy_consumption.csv
│
├── models/
│   ├── linear_regression.pkl
│   ├── random_forest.pkl
│   └── xgboost_model.pkl
│
├── app.py
├── train_model.py
├── requirements.txt
├── README.md
│
└── assets/
    └── screenshots/
```

---

## 🔄 Workflow

### 1. Data Collection

Historical electricity consumption data is collected and stored for analysis.

### 2. Data Preprocessing

* Handling missing values
* Data cleaning
* Feature engineering
* Data normalization

### 3. Model Training

Three machine learning models are trained and evaluated:

* Linear Regression
* Random Forest Regressor
* XGBoost Regressor

### 4. Prediction

The best-performing model is used to forecast future energy consumption.

### 5. Wastage Detection

Consumption values significantly deviating from expected patterns are flagged as potential energy wastage.

### 6. Visualization

Interactive charts and graphs help users understand:

* Consumption trends
* Predicted usage
* Wastage patterns
* Model performance

---

## 📊 Machine Learning Pipeline

```text
Raw Data
   │
   ▼
Data Cleaning
   │
   ▼
Feature Engineering
   │
   ▼
Train/Test Split
   │
   ▼
Model Training
   │
   ├── Linear Regression
   ├── Random Forest
   └── XGBoost
   │
   ▼
Model Evaluation
   │
   ▼
Prediction & Wastage Detection
   │
   ▼
Streamlit Dashboard
```

---

## 📈 Key Insights Generated

* Daily energy consumption trends
* Peak consumption periods
* Consumption forecasting
* Energy wastage identification
* Efficiency improvement opportunities
* Cost optimization recommendations

---

## 🎯 Business Impact

* Reduces unnecessary energy consumption
* Identifies potential wastage early
* Supports energy-efficient decision making
* Helps lower electricity costs
* Promotes sustainable energy management

---

## 🖥️ Installation & Setup

### Clone the Repository

```bash
git clone https://github.com/your-username/smart-energy-consumption-predictor.git

cd smart-energy-consumption-predictor
```

### Create Virtual Environment

```bash
python -m venv venv
```

### Activate Environment

**Windows**

```bash
venv\Scripts\activate
```

**Linux/Mac**

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Application

```bash
streamlit run app.py
```

---

## 📊 Model Evaluation Metrics

The models are evaluated using:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score

The best-performing model is selected for deployment.

---

## 🔮 Future Enhancements

* Deep Learning-based forecasting (LSTM)
* Real-time IoT sensor integration
* Smart energy consumption recommendations
* Automated alert system for abnormal usage
* Cloud deployment and monitoring
* Energy cost forecasting

---

## 👨‍💻 Author

**Sai Shiva Merugu**

* B.Tech (CSE - AI & ML)
* Machine Learning Enthusiast
* Passionate about Data Analytics and Intelligent Systems

📧 Email: [saishiva6638@gmail.com](mailto:saishiva6638@gmail.com)

---

## 📜 License

This project is developed for educational and learning purposes. Feel free to use and modify it for academic or personal projects.

⭐ If you found this project useful, consider giving it a star on GitHub!
