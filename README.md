# 🏡 Housing Price Prediction

This project predicts housing prices using the **Boston Housing Dataset** by applying three different regression models:  
**Linear Regression (from scratch)**, **Random Forest**, and a **simplified XGBoost**.

---

## 📁 Dataset

- **Name:** Boston Housing Dataset  
- **Download:** [HousingData.csv](https://raw.githubusercontent.com/selva86/datasets/master/BostonHousing.csv)

---

## 📊 Features

The dataset contains information on housing in Boston suburbs with features such as:
- Crime rate, average number of rooms, property tax rate, distance to employment centers, etc.
- **Target Variable:** `MEDV` — Median value of owner-occupied homes (in $1000s)

---

## 🔧 Workflow

1. **Data Preprocessing**
   - Handle missing values by replacing with mean
   - One-hot encoding for categorical features
   - Standardize features using `StandardScaler`
   - Split data into 80% training and 20% testing

2. **Model Implementation**
   - ✅ Linear Regression from scratch (Normal Equation)
   - ✅ Random Forest with bootstrap sampling and random feature selection
   - ✅ XGBoost (simplified gradient boosting using residuals)

3. **Model Evaluation**
   - Metrics: **RMSE (Root Mean Squared Error)** and **R² Score**
   - Visualize feature importances for Random Forest and XGBoost

---

## 🚀 Results

- All models successfully predicted housing prices.
- **XGBoost** performed best in terms of RMSE and R² score.
- Feature importance plots highlight key variables impacting housing prices.

---

## 📦 Libraries Used

- Python
- NumPy
- Pandas
- Scikit-learn
- Matplotlib

---

## 🚀 How to Run the Notebook

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/predicting-house-prices-using-the-boston-housing-dataset.git
   cd predicting-house-prices-using-the-boston-housing-dataset
   ```

2. **Install Required Packages**
   Make sure you have Python 3.12.8 and Jupyter Notebook installed. You can install the required libraries using pip:

   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn joblib
   ```

3. **Launch the Notebook**
   ```bash
   jupyter notebook main.ipynb
   ```

4. **Explore the Analysis**
   - Follow each step in the notebook to see the data loading, cleaning, visualization, and insights process.
