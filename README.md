# 🚗 Tesla Stock Price Prediction using Python & Machine Learning

This project focuses on analyzing and predicting **Tesla Inc. (TSLA)** stock prices using **Linear Regression**. It demonstrates how simple machine learning models can be used to understand trends in stock data and make basic forecasts.

---

## 📌 Objective

- Visualize historical stock data for Tesla
- Build a **Linear Regression** model to predict closing prices
- Evaluate the model using **R² Score** and **Mean Squared Error (MSE)**
- Provide an easy-to-understand learning example for beginners in data science

---

## 🛠️ Tools & Libraries Used

- Python
- Jupyter Notebook
- `pandas` – data manipulation  
- `numpy` – numerical operations  
- `matplotlib` / `plotly` – data visualization  
- `scikit-learn` – machine learning and model evaluation  

---

## 📊 Dataset

The dataset includes Tesla stock data with the following columns:
- Date
- Open, High, Low, Close prices
- Adjusted Close
- Volume

**Source**: [Yahoo Finance – Tesla (TSLA)](https://finance.yahoo.com/quote/TSLA/history/)

---

## 🔁 Workflow

### 1. Data Preprocessing
- Loaded the CSV file into a Pandas DataFrame
- Handled date formatting and index setting
- Checked for missing values

### 2. Visualization
- Used Plotly to plot Tesla’s closing prices over time
- Customized plot layout for better readability

### 3. Model Building
- Converted dates into numerical format using index
- Split the dataset into training (70%) and testing (30%) sets
- Trained a **Linear Regression** model using `scikit-learn`

### 4. Model Evaluation
- Compared predicted vs actual closing prices for training data
- Evaluated the model using:
  - **R² Score**
  - **Mean Squared Error (MSE)**

### 5. Result Visualization
- Created interactive Plotly charts showing:
  - Actual vs Predicted stock prices

---

## 📉 Sample Output

```text
Metric     Train                 Test
r2_score   0.9862                0.9821
MSE        104.75               116.48
