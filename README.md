# 📊 Exploratory Data Analysis of Student Academic Performance

## 📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on a Student Performance dataset containing information about students' academic performance, demographics, family background, study habits, and social factors.

The main objective is to explore the dataset, identify patterns and trends, calculate statistical summaries, visualize relationships between variables, and analyze factors associated with students' final academic performance.

The final grade (`G3`) is used as the primary performance variable throughout the analysis.

---

## 🎯 Problem Statement

Student academic performance can be influenced by various academic, demographic, family, and social factors.

This project aims to explore student performance data and identify patterns, relationships, and factors associated with students' final grades.

The analysis examines variables such as study time, absences, previous failures, parental education, previous grades, internet access, and higher-education plans.

---

## 🎯 Objectives

- Understand the structure and characteristics of the dataset.
- Check the dataset for missing values and duplicate records.
- Perform statistical analysis of numerical variables.
- Analyze the distribution of students' final grades.
- Explore relationships between student characteristics and academic performance.
- Analyze study time and its relationship with final grades.
- Examine absences and previous failures.
- Study parental education and academic performance.
- Analyze the relationship between previous grades and final grades.
- Perform correlation analysis.
- Create meaningful visualizations.
- Summarize the major findings from the analysis.

---

## 📂 Dataset

The dataset contains:

- **395 student records**
- **33 features**

The features include information related to:

- Student demographics
- Family background
- Study habits
- Academic history
- School-related information
- Social activities
- Absences
- Previous grades
- Final grade

### Important Variables

| Variable | Description |
|---|---|
| `school` | Student's school |
| `sex` | Student's gender |
| `age` | Student's age |
| `studytime` | Weekly study time |
| `failures` | Number of past class failures |
| `Medu` | Mother's education |
| `Fedu` | Father's education |
| `internet` | Internet access |
| `absences` | Number of school absences |
| `G1` | First-period grade |
| `G2` | Second-period grade |
| `G3` | Final grade |

---

## 🛠️ Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 🔍 EDA Process

The project follows these major steps:

### 1. Data Loading
The dataset is loaded using Pandas.

### 2. Data Understanding
The dataset shape, columns, data types, and sample records are examined.

### 3. Data Quality Check
Missing values and duplicate records are checked.

### 4. Statistical Analysis
Descriptive statistics such as mean, minimum, maximum, standard deviation, and quartiles are calculated.

### 5. Univariate Analysis
Individual variables are explored using statistical summaries and visualizations.

### 6. Bivariate Analysis
Relationships between selected variables and final grade are analyzed.

### 7. Correlation Analysis
Numerical correlations with the final grade are calculated and visualized using a heatmap.

### 8. Insights
Important patterns and relationships identified during the analysis are summarized.

---

## 📊 Visualizations

The project includes several types of visualizations:

- Histograms
- Bar charts
- Box plots
- Scatter plots
- Regression plots
- Correlation heatmaps

These visualizations are used to understand distributions, compare groups, and examine relationships between variables.

---

## 📈 Key Findings

The analysis produced several notable findings from the dataset:

- The average final grade (`G3`) is **10.42 out of 20**.
- The minimum final grade is **0**, while the maximum is **20**.
- `G2` has a correlation of approximately **0.905** with `G3`.
- `G1` has a correlation of approximately **0.801** with `G3`.
- Previous failures have a correlation of approximately **-0.360** with `G3`.
- Mother's education (`Medu`) has a correlation of approximately **0.217** with `G3`.
- Father's education (`Fedu`) has a correlation of approximately **0.152** with `G3`.
- Study time has a relatively small positive correlation of approximately **0.098** with `G3`.
- Absences have a correlation of approximately **0.034** with `G3`.
- Students with internet access have an average final grade of approximately **10.62**, compared with **9.41** for students without internet access.
- Students who reported wanting higher education have an average final grade of approximately **10.61**, compared with **6.80** for those who did not.

These findings describe relationships observed within this dataset. Correlation does not establish causation.

---

## 💡 Insights

The analysis shows that previous academic grades have strong positive relationships with final grades in this dataset.

The number of previous failures shows a negative relationship with final grade. Differences can also be observed across groups based on parental education, internet access, study time, and higher-education plans.

These results demonstrate how EDA can be used to explore a dataset and identify potentially important patterns in student academic performance.

---

## ⚠️ Limitations

- The dataset contains 395 student records.
- The dataset represents a specific student population and may not represent all students.
- Correlation does not imply causation.
- Relationships between variables may be influenced by other factors.
- The findings should be interpreted within the context of the available dataset.

---

## 🏁 Conclusion

This project demonstrates the use of Exploratory Data Analysis to investigate student academic performance.

Through statistical analysis and visualization, the project explored demographic, academic, family, and social variables and examined their relationships with final grades.

The analysis demonstrates how Python-based data analysis tools can be used to transform raw data into meaningful insights and support data-driven understanding of a problem.

---

## 📁 Project Structure

```text
EDA-Student-Performance/
│
├── student_data.csv
├── EDA_Student_Performance.ipynb
└── README.md
