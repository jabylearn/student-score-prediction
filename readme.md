# Student Performance Prediction Using Linear Regression

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 📌 Project Overview

This project aims to predict student exam scores based on the number of hours studied using the Linear Regression Machine Learning algorithm.

The project follows a complete Data Science and Machine Learning pipeline, including data collection, data cleaning, exploratory data analysis (EDA), feature selection, model training, evaluation, and business insights generation.

The primary goal is to understand how study hours influence academic performance and build a predictive model capable of estimating student marks.

---

## 🎯 Business Problem

Educational institutions often need a way to estimate student performance before examinations.

This project addresses the following questions:

- Does studying longer improve exam scores?
- How strong is the relationship between study hours and marks?
- Can student scores be predicted using study hours?
- How accurate is the prediction model?

---

## 🎯 Project Objectives

### Primary Objective

Build a Machine Learning model using Linear Regression to predict student exam scores based on study hours.

### Secondary Objectives

- Analyze the relationship between study hours and marks.
- Perform exploratory data analysis.
- Visualize data patterns and trends.
- Train and evaluate a Linear Regression model.
- Generate meaningful business insights.
- Predict scores for new students based on study hours.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

---

## 📂 Project Structure

```text
student-performance-prediction/
│
├── data/
│   └── student_scores.csv
│
├── notebooks/
│   └── student_performance.ipynb
│
├── images/
│   ├── study_hours_histogram.png
│   ├── marks_histogram.png
│   ├── scatter_plot.png
│   ├── heatmap.png
│   └── regression_line.png
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## 📊 Dataset Information

| Feature | Description |
|----------|------------|
| Hours | Number of study hours |
| Marks | Student exam score |

### Dataset Size

- Records: 25
- Features: 1
- Target Variable: Marks

---

## 🔄 Machine Learning Pipeline

### 1. Business Understanding

- Defined project goals
- Identified feature and target variables

### 2. Data Collection

- Student performance dataset

### 3. Data Understanding

- Dataset inspection
- Data type analysis
- Statistical summary

### 4. Data Cleaning

- Missing value detection
- Duplicate value detection
- Outlier analysis

### 5. Exploratory Data Analysis (EDA)

- Study Hours Distribution
- Marks Distribution
- Scatter Plot Analysis
- Correlation Analysis
- Heatmap Visualization

### 6. Feature Selection

```python
X = df[['Hours']]
y = df['Marks']
```

### 7. Train-Test Split

```python
train_test_split(
    X,
    y,
    test_size=0.2,
    random_state=42
)
```

### 8. Model Building

Algorithm Used:

```python
LinearRegression()
```

### 9. Model Evaluation

Metrics:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

---

## 📈 Exploratory Data Analysis

### Study Hours Distribution

Analyzed how students distribute their study time.

### Marks Distribution

Analyzed score distribution across students.

### Scatter Plot

Observed a clear positive linear relationship between study hours and marks.

### Correlation Heatmap

Correlation between Hours and Marks:

```text
0.98
```

This indicates a very strong positive relationship.

---

## 🤖 Model Used

### Linear Regression

Linear Regression attempts to fit the best straight line through the data.

Formula:

\[
y = mx + b
\]

Where:

- y = Predicted Marks
- x = Study Hours
- m = Slope
- b = Intercept

---

## 📊 Results

### Key Findings

- Strong positive relationship between study hours and marks.
- Correlation coefficient of approximately 0.98.
- Students who study more tend to score higher.
- Linear Regression effectively models the relationship.

### Model Performance

| Metric | Value |
|----------|--------|
| MAE | Your Result |
| RMSE | Your Result |
| R² Score | Your Result |

---

## 💡 Business Insights

- Study hours are a significant predictor of academic performance.
- Students with low study hours can be identified early for intervention.
- The model can assist coaching institutes in tracking student progress.
- Predictive analytics can support educational decision-making.

---

## 🚀 Future Scope

The current model uses only one feature:

- Study Hours

Future improvements may include:

- Attendance Percentage
- Assignment Scores
- Previous Semester Marks
- Sleep Duration
- Classroom Participation
- Study Environment Factors

Using multiple features can improve prediction accuracy.

---

## ▶️ How to Run

### Clone Repository

```bash
git clone https://github.com/yourusername/student-performance-prediction.git
```

### Navigate to Project Folder

```bash
cd student-performance-prediction
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Notebook

```bash
jupyter notebook
```

---

## 👨‍💻 Author

**Murshida Jabeen P K**

Data Science & Machine Learning Enthusiast

---

## ⭐ Project Status

✅ Completed

This project was developed as part of a Machine Learning learning journey to understand the complete workflow of building and evaluating predictive models using Linear Regression.