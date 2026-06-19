# Titanic_data
# 🚢 Titanic Data Analysis Project

---

## 📊 Project Overview

This project performs **Exploratory Data Analysis (EDA)** and **Data Cleaning** on the famous Titanic dataset to uncover patterns that influenced passenger survival.

We analyze how factors like **gender, age, passenger class, and fare** impacted survival outcomes.

---

## 📁 Dataset

We use the Titanic dataset from Kaggle:

- Passenger information
- Survival status
- Ticket class
- Age, Sex, Fare, Embarked location

---

## 🎯 Objectives

- Clean and preprocess raw dataset
- Handle missing values and outliers
- Encode categorical features
- Perform feature scaling
- Conduct Exploratory Data Analysis (EDA)
- Identify key survival patterns

---

## 🛠️ Tools & Libraries

- Python 🐍  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Google Colab  

---

## 🧹 Data Cleaning Process

✔ Filled missing values in **Age** using median  
✔ Filled missing values in **Embarked** using mode  
✔ Dropped **Cabin** column due to excessive missing data  
✔ Removed outliers in **Fare** using IQR method  
✔ Encoded categorical variables (Sex, Embarked)  
✔ Scaled numerical features using MinMaxScaler  

---

## 📊 Exploratory Data Analysis (EDA)

### 🔹 Survival Distribution
![Survival Chart](https://via.placeholder.com/600x300.png?text=Survival+Count+Plot)

### 🔹 Gender vs Survival
![Gender Plot](https://via.placeholder.com/600x300.png?text=Gender+vs+Survival)

### 🔹 Age Distribution
![Age Plot](https://via.placeholder.com/600x300.png?text=Age+Distribution)

### 🔹 Correlation Heatmap
![Heatmap](https://via.placeholder.com/600x300.png?text=Correlation+Heatmap)

---

## 🔗 Key Insights

- 👩 Female passengers had a higher survival rate than males  
- 💰 Higher fare increased chances of survival  
- 🏆 1st class passengers survived more than lower classes  
- 👶 Younger passengers had slightly better survival chances  
- 📉 Strong correlation between **Pclass, Sex, and Survival**

---

## 📦 Project Structure
