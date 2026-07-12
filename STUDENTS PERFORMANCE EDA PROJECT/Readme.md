# 📊 Student Performance - Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on a Student Performance dataset using Python. The objective is to understand the factors affecting students' academic performance by analyzing different variables such as gender, parental education, lunch type, and subject scores.

The project includes data cleaning, descriptive statistics, visualization, and insights to identify meaningful patterns in the dataset.

---

## 🎯 Objectives

- Explore the structure of the dataset.
- Check for missing and duplicate values.
- Perform descriptive statistical analysis.
- Visualize the distribution of student scores.
- Compare performance based on gender.
- Identify important trends and patterns.

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 📚 Libraries Used

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
```

---

## 📂 Project Structure

```
Student-Performance-EDA/
│
├── Student_Performance_EDA.ipynb
├── StudentsPerformance.csv
├── images/
│   ├── dataset_preview.png
│   ├── missing_values.png
│   ├── descriptive_statistics.png
│   ├── reading_distribution.png
│   ├── average_math_gender.png
│   ├── reading_vs_average_score.png
│   └── writing_boxplot.png
│
└── README.md
```

---

## 📊 Dataset Information

The dataset contains information about students including:

- Gender
- Race/Ethnicity
- Parental Level of Education
- Lunch Type
- Test Preparation Course
- Math Score
- Reading Score
- Writing Score

**Total Records:** 1000

---

# 🔍 Analysis Performed

### ✔ Data Loading

- Imported the dataset using Pandas.
- Displayed the first five rows.

### ✔ Data Exploration

- Checked dataset shape.
- Examined column names.
- Verified data types.

### ✔ Data Cleaning

- Checked for missing values.
- Checked for duplicate records.
- Confirmed the dataset is clean for analysis.

### ✔ Descriptive Statistics

Calculated:

- Count
- Mean
- Standard Deviation
- Minimum
- Maximum
- Quartiles

### ✔ Data Visualization

Created visualizations to better understand the data:

- Reading Score Distribution (Histogram)
- Average Math Score by Gender (Bar Chart)
- Reading Score vs Average Score (Scatter Plot)
- Writing Score Distribution (Box Plot)

---

# 💡 Key Insights

- The dataset contains **1000 student records**.
- No missing values were found.
- No duplicate records were found.
- Male students achieved slightly higher average Math scores.
- Reading scores show a strong positive relationship with overall student performance.
- Writing scores are concentrated around the middle range with a few lower-score outliers.
- Most students scored between **60 and 80 marks**.

---

## 🚀 Future Improvements

- Perform correlation analysis.
- Build machine learning models for score prediction.
- Create an interactive dashboard using Power BI or Streamlit.
- Add more advanced visualizations.
- Perform feature engineering for predictive analysis.

---

## 👩‍💻 Author

**Janvi Govind Patil**

B.Tech Data Science Student

GitHub: https://github.com/janvigpatil25

LinkedIn: https://www.linkedin.com/in/janvi-patil-941509419

---

## ⭐ If you found this project useful, consider giving it a Star!