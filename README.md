# 🏠 House Price Prediction

## 📌 Project Overview
This project focuses on *predicting house prices* using data analysis and machine learning techniques.  
The workflow includes:
- Data loading & cleaning  
- Exploratory Data Analysis (EDA)  
- Feature engineering  
- Feature scaling  
- Building a *Linear Regression model* to predict house prices  

---

## 📂 Steps in the Notebook

### 1️⃣ Import Libraries
- Imported essential Python libraries: *pandas, numpy, seaborn, matplotlib, warnings*  
- Used for data handling, numerical operations, visualization 

### 2️⃣ Load Dataset & Initial Exploration
- Loaded the dataset: *Housing.csv*  
- Checked:
  - Column names  
  - Dataset shape (rows & columns)  
  - First & last 5 rows (head(), tail())  
  - Info of dataset (info())  
  - Statistical summary (describe())  
  - Count of unique values (nunique())  

### 3️⃣ Data Visualization (EDA)
- Used *Seaborn & Matplotlib* for visual insights:
  - Distribution plots of features  
  - Scatter plots   
  - Correlation heatmap  

### 4️⃣ Handling Categorical Variables
- Converted categorical columns into numerical using *encoding*    

### 5️⃣ Feature Scaling
- Applied *StandardScaler* to normalize feature values and created X_scaled  

### 6️⃣ Train-Test Split
- Split data into:
  - *Training set → 80%*  
  - *Testing set → 20%*  

### 7️⃣ Model Training – Linear Regression
- Trained a *Linear Regression* model  
- Evaluated performance using metrics:
  - Mean Squared Error (MSE)  
  - Root Mean Squared Error (RMSE)  
  - Mean Absolute Error (MAE)  
  - R-squared (R²)  

---

## 🚀 Key Learnings
- Cleaning & exploring a housing dataset  
- Understanding EDA   
- Applying *feature scaling* before model training  
- Training & evaluating a *Linear Regression* model  

---

## 🛠 Tools & Libraries
- *Python*  
- *pandas, numpy* → Data handling  
- *seaborn, matplotlib* → Visualization  
- *sklearn* → Scaling, Train-Test Split, Linear Regression, Metrics  
