# 🏡 Task 3: Predicting House Prices with Linear Regression

## 📌 Objective
Build a machine learning model using **Linear Regression** to predict housing prices based on relevant numerical features from a dataset.

---

## 📂 Dataset
- **File**: `Housing.csv`
- **Source**: Provided by Oasis InfoByte for internship project
- Contains various features such as price, number of bedrooms, bathrooms, size, etc.

---

## 🔧 Workflow Steps

1. **Data Import and Exploration**
   - Loaded the CSV using `pandas`
   - Explored basic stats, null values, and feature types

2. **Data Preprocessing**
   - Handled missing values (if any)
   - Converted categorical variables using encoding (if applicable)
   - Separated feature variables (X) and target variable (y)

3. **Model Building**
   - Split the dataset into training and testing sets
   - Used `LinearRegression` from `sklearn` to build the model

4. **Model Evaluation**
   - Calculated R² Score and Root Mean Squared Error (RMSE)
   - R² Score achieved: **0.65**
   - RMSE: **1,324,506.96**

5. **Conclusion & Insights**
   - The model explains ~65% of the variation in house prices.
   - Further improvements could be made using:
     - Feature engineering
     - Regularization techniques (Ridge, Lasso)
     - More data or higher-quality features

---

## 📊 Tools & Libraries Used
- Python
- Jupyter Notebook
- Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn (`LinearRegression`, `trai
