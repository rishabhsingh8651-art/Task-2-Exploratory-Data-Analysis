# Task 2: Exploratory Data Analysis (EDA)

## 📌 Objective

The objective of this task is to perform Exploratory Data Analysis (EDA)
to understand the dataset using descriptive statistics and data
visualizations.

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

## 📊 Dataset

For this task, the Titanic dataset was used for Exploratory Data Analysis.

The dataset contains information about passengers, including:

- PassengerId
- Survived
- Pclass
- Name
- Sex
- Age
- SibSp
- Parch
- Ticket
- Fare
- Cabin
- Embarked

## 🔍 EDA Performed

The following analysis was performed:

1. Loaded and explored the dataset.
2. Checked dataset shape and data types.
3. Analyzed missing values.
4. Generated descriptive statistics.
5. Calculated mean, median, and standard deviation.
6. Created histograms for numerical features.
7. Created boxplots to identify potential outliers.
8. Analyzed categorical features.
9. Analyzed survival patterns.
10. Created pairplots to understand feature relationships.
11. Created a correlation matrix.
12. Analyzed skewness of numerical features.
13. Identified patterns, trends, and potential anomalies.
14. Added feature-level observations based on visualizations.

## 📈 Key Observations

- The Age feature contains passengers from different age groups.
- The Fare feature shows a right-skewed distribution with some high-value observations.
- Passenger classes have different distributions.
- Survival patterns vary across passenger groups.
- Gender and passenger class show differences in survival patterns.
- The correlation matrix helps identify relationships between numerical features.
- Boxplots help identify potential outliers in numerical features.

## 📁 Project Structure

```text
Task-2-Exploratory-Data-Analysis/
│
├── DATA/
│   └── Titanic-Dataset.csv
│
├── Task-2-EDA.ipynb
│
└── README.md