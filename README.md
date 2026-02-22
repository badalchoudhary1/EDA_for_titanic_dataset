🚢 Exploratory Data Analysis (EDA) on Titanic Dataset
📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on the famous Titanic Dataset, which contains information about passengers aboard the RMS Titanic.

The goal of this analysis is to explore patterns, detect relationships between variables, and understand the factors that influenced passenger survival.

🎯 Objectives

Understand the structure and distribution of the dataset

Handle missing values and clean the data

Analyze survival patterns

Identify important features affecting survival

Visualize relationships between variables

📂 Dataset Information

The dataset typically includes the following features:

PassengerId – Unique ID for each passenger

Survived – Survival status (0 = No, 1 = Yes)

Pclass – Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)

Name – Passenger name

Sex – Gender

Age – Age in years

SibSp – Number of siblings/spouses aboard

Parch – Number of parents/children aboard

Ticket – Ticket number

Fare – Passenger fare

Cabin – Cabin number

Embarked – Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

🔍 Exploratory Data Analysis Steps
1️⃣ Data Understanding

Checked dataset shape and data types

Reviewed summary statistics

Identified missing values

2️⃣ Data Cleaning

Handled missing values in Age, Cabin, and Embarked

Treated categorical variables

Removed or transformed irrelevant features

3️⃣ Univariate Analysis

Distribution of Age

Gender distribution

Passenger class distribution

Survival distribution

4️⃣ Bivariate Analysis

Survival vs Gender

Survival vs Passenger Class

Survival vs Age

Survival vs Fare

Correlation heatmap

📊 Key Insights

👩 Females had a significantly higher survival rate than males

🥇 Passengers in 1st class had higher survival rates

👶 Children had better survival chances

💰 Higher fare passengers were more likely to survive

🚢 Port of embarkation showed slight variation in survival rates

🛠️ Tools & Libraries Used

Python

Pandas

NumPy

Matplotlib

Seaborn

📈 Conclusion

The EDA revealed that gender, passenger class, age, and fare were strong indicators of survival. These insights can be used for feature engineering and building predictive models such as Logistic Regression, Random Forest, or other classification algorithms.
