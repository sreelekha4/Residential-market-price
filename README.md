# 🏠 Residential Market Price Forecast Using Machine Learning

## 📌 Overview
This project builds a **Machine Learning model** to predict house prices based on various features such as area, number of bedrooms, and other property-related attributes.

The goal is to understand **how different factors influence house prices** and create a predictive model using **Linear Regression**.

---

## 📂 Dataset Information
- **File:** `train.csv`  
- **Rows:** Multiple
- **Columns:** Multiple  

### **Key Features:**
- `POSTED_BY`
- `UNDER_CONSTRUCTION`
- `RERA`
- `BHK_NO`
- `BHK_OR_RK	SQUARE_FT`
- `READY_TO_MOVE`
- `RESALE`
- `ADDRESS`
- `LONGITUDE`
- `LATITUDE`
- `TARGET(PRICE_IN_LACS)`

---

## 🛠️ Technologies Used
- Python 🐍  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Jupyter Notebook  

---

## 🔍 Project Workflow

### 1. Data Loading
- Loaded dataset using Pandas  
- Checked structure, shape, and data types  

### 2. Data Cleaning
- Checked for missing values  
- Handled inconsistencies (if any)  
- Converted categorical variables into numerical format (if required)  

### 3. Feature Engineering
- Selected relevant features for prediction  
- Encoded categorical variables  
- Split data into:
  - Training set  
  - Testing set  

---

## 🤖 Model Building

- Used **Linear Regression** algorithm  
- Trained model on training data  
- Predicted house prices on test data  

---

## 📊 Model Evaluation

Evaluated model performance using:

- Mean Absolute Error (MAE)  
- Mean Squared Error (MSE)  
- R² Score  

These metrics help in understanding the accuracy and reliability of the model.

---

## 📊 Key Insights

- 🏠 **Area is the most influential factor** in determining house prices  
- 🛏️ More bedrooms and bathrooms generally increase price  
- 🚗 Parking availability positively impacts price  
- 📈 Strong linear relationship between features and price  

---

## 📌 Visualizations

The notebook includes:

- Scatter plots 📉  
- Regression plots 📈  
- Heatmaps 🔥
- and many more 

These visualizations help in identifying relationships between variables and price trends.

---

