# 🏡 Housing Price Prediction

This project predicts housing prices using the **Boston Housing Dataset** by applying three different regression models:  
**Linear Regression (from scratch)**, **Random Forest**, and a **simplified XGBoost**.

---

## 📁 Dataset

- **Name:** Boston Housing Dataset  
- **Download:** [HousingData.csv](https://www.kaggle.com/datasets/altavish/boston-housing-dataset)

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

---

## ✅ Conclusion

This project successfully demonstrates a complete workflow for **house price prediction** using the Boston Housing dataset, featuring:

- **Data Preprocessing**: Normalized all numerical features and handled missing values to ensure clean inputs.
- **Custom Model Implementations**: Built three regression models from scratch—  
  - **Linear Regression** (closed‑form solution),  
  - **Random Forest** (bagged decision trees),  
  - **XGBoost‑style Gradient Boosting**.
- **Performance Comparison**: Evaluated each model on the test set using **RMSE** and **R²**, highlighting trade‑offs between bias and variance.
- **Feature Importance Analysis**: Visualized the most influential predictors for the tree‑based models, offering insights into which factors drive housing prices.

Key takeaways:
- The **Linear Regression** baseline provides interpretable coefficients but may under‑fit complex relationships.
- **Random Forest** reduces variance and captures nonlinear effects, improving predictive accuracy.
- The **XGBoost‑style model** further refines residual errors through iterative boosting, often yielding the lowest error.

Overall, this project showcases practical skills in **from‑scratch algorithm implementation**, **model evaluation**, and **interpretability**—essential techniques for real‑world regression tasks and data‑driven decision making. ```
