# Titanic Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project presents a comprehensive Exploratory Data Analysis (EDA) of the Titanic dataset obtained from Kaggle. The goal of the analysis is to understand the structure of the dataset, explore patterns and relationships among variables, and identify key factors that influenced passenger survival during the Titanic disaster.

The notebook follows a structured EDA workflow, combining statistical analysis with data visualization to derive meaningful insights.

---

## 🎯 Objectives
The main objectives of this project are to:
- Understand the dataset structure and feature characteristics
- Handle missing values and detect outliers
- Perform univariate, bivariate, and multivariate analysis
- Explore the target variable (`Survived`) and identify influential factors
- Provide insights that can support future predictive modeling

---

## 📊 Dataset
- **Source:** Kaggle – Titanic: Machine Learning from Disaster
- **File used:** `train.csv`
- **Description:** The dataset contains demographic, socio-economic, and travel-related information for passengers aboard the Titanic.

---

## 🛠️ Tools & Technologies
- **Programming Language:** Python
- **Libraries Used:**
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
- **Environment:** Kaggle Notebook

---

## 🔍 Analysis Workflow
The analysis follows these key steps:

1. **Initial Data Exploration**
   - Dataset overview using shape, info, and summary statistics
   - Feature profiling and duplicate checks

2. **Data Cleaning**
   - Handling missing values (Age, Embarked)
   - Dropping features with excessive missing data (Cabin)

3. **Univariate Analysis**
   - Distribution analysis of individual features such as Age, Fare, Embarked, and Survived

4. **Bivariate Analysis**
   - Relationship analysis between pairs of variables (e.g., Fare vs Pclass, Age vs Survival)

5. **Multivariate Analysis**
   - Interaction effects among multiple variables including Age, Fare, Gender, and Passenger Class

6. **Outlier Detection & Handling**
   - Identification of outliers in Fare and Age
   - Justified handling using retention and capping techniques

7. **Target Variable Exploration**
   - Survival analysis by gender, passenger class, and their combined effects

---

## 📈 Key Insights
- Survival was highly influenced by **gender** and **passenger class**
- Females and first-class passengers had significantly higher survival rates
- Fare and age also contributed to survival outcomes
- Multivariate analysis revealed strong interaction effects between socio-economic and demographic factors

---

## 📌 Conclusion
This exploratory data analysis highlights how demographic and socio-economic factors influenced survival on the Titanic. The insights gained provide a strong foundation for future predictive modeling and machine learning applications.

---

## 📁 Repository Contents
- `Titanic_EDA_Assignment.ipynb` – Complete EDA notebook with code, visualizations, and explanations
- `README.md` – Project documentation

---

## 🔗 References
- Kaggle Titanic Dataset: https://www.kaggle.com/competitions/titanic

---

## 👤 Author
**Eugene**  
Student | Data Science Enthusiast  

# Titanic-Exploratory-Analysis
Exploratory data analysis of the titanic dataset using python

