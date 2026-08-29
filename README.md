# EcoYield: Multi-Region Renewable Energy Generation Forecaster

An end-to-end machine learning application designed to accurately forecast solar power generation using historical weather and environmental data. Built to optimize energy production, plan resource allocation, and support decision-making in solar energy management.

## 🚀 Project Objective
The objective of this project is to accurately predict solar power generation using historical weather and environmental data. By leveraging machine learning, specifically the Gradient Boosting algorithm, the project aims to provide reliable predictions of the power output from solar panels to support effective solar energy management.

---

## 🛠️ Tech Stack
* **Language:** Python
* **Machine Learning:** Scikit-Learn, Gradient Boosting Regressor, Pandas, NumPy
* **Data Visualization & Interface:** Streamlit, Matplotlib, Plotly
* **Version Control:** Git & GitHub

---

## 📊 Exploratory Data Analysis (EDA)
Extensive Exploratory Data Analysis (EDA) was conducted to understand the relationships between various weather parameters and solar power generation. Key steps included:
* **Data Cleaning:** Handling missing values and outliers to ensure top-tier data quality.
* **Feature Engineering:** Creating new features such as average wind speed and pressure over specific periods to enhance model performance.
* **Data Visualization:** Utilizing plots and graphs to explore correlations between features like temperature, humidity, wind speed, and power generation.

These insights helped select the most relevant features for model training and uncover underlying patterns in the dataset.

---

## 🤖 Model Implementation
The predictive model was built using the Gradient Boosting algorithm, a powerful machine learning technique that combines the predictions of several base estimators to improve accuracy and robustness. 

* **Model Training:** The Gradient Boosting Regressor was trained on the preprocessed data, optimizing hyperparameters to achieve peak performance.
* **Model Evaluation:** Evaluated using metrics like Mean Squared Error (MSE) and R-squared (R²) to ensure high accuracy and reliability.

---

## 💻 Deployment Using Streamlit
To make the model accessible and easy to use, a web application was developed using Streamlit, providing a user-friendly interface where users can input weather data and instantly receive predictions.

* **Interactive Input Form:** Users can enter parameters such as temperature, wind speed, and sky cover.
* **Real-Time Predictions:** Processes input data to display predicted power generation in kilowatts instantly.
* **Dynamic Visualization:** Includes visual elements to enhance user experience, displaying relevant insights and output results.

---

## ⚙️ Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/SAMEERSHARMA2804/EcoYield-Renewable-Forecaster.git](https://github.com/SAMEERSHARMA2804/EcoYield-Renewable-Forecaster.git)
   cd EcoYield-Renewable-Forecaster
   Install dependencies:

Bash
pip install -r requirements.txt
Run the Streamlit application:

Bash
streamlit run app.py



👤 Author
Sameer Sharma

B.Tech CSE (Data Science) | Ex-Paytm Data & ML Intern

