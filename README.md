# 📊 Student Performance Analysis

A beginner-friendly data analysis and machine learning project exploring the relationship between students' study habits, attendance, previous academic performance, sleep, and exam scores.

## 📌 Overview

The goal of this project is to demonstrate a basic end-to-end data analysis workflow using Python.

The project explores questions such as:

* Does studying more relate to higher exam scores?
* Is attendance associated with academic performance?
* How does previous academic performance relate to current scores?
* Is there a relationship between sleep and exam performance?
* Can exam scores be approximately estimated using basic machine learning?

The project combines **exploratory data analysis (EDA)** with a simple **Linear Regression** model.

## 🛠️ Technologies Used

* **Python**
* **Pandas** — data manipulation and analysis
* **NumPy** — numerical operations
* **Matplotlib** — data visualization
* **Scikit-learn** — machine learning

## 📂 Project Structure

```text
Student-Performance-Analysis/
│
├── Student_Performance_Analysis.ipynb
└── README.md
```

## 📊 Dataset

The project uses a small structured dataset containing information about student:

* Study hours
* Attendance percentage
* Previous academic score
* Sleep hours
* Exam score

**Note:** The current dataset is a small demonstration dataset created for learning purposes. The results should not be interpreted as conclusions about real-world student populations.

## 🔍 Analysis Performed

### 1. Data Inspection

The dataset is inspected using Pandas to understand:

* Number of observations and features
* Data types
* Summary statistics
* Missing values

### 2. Exploratory Data Analysis

Visualizations are used to explore relationships between variables.

Examples include:

* Study Hours vs Exam Score
* Attendance vs Exam Score
* Correlation between numerical variables

### 3. Correlation Analysis

A correlation matrix is calculated to identify the strength and direction of relationships between the variables.

### 4. Machine Learning

A **Linear Regression** model is trained using:

* Study Hours
* Attendance
* Previous Score
* Sleep Hours

The model is evaluated using:

* **Mean Absolute Error (MAE)**
* **R² Score**

## 🔄 Workflow

```text
Dataset
   ↓
Data Inspection
   ↓
Data Cleaning
   ↓
Exploratory Data Analysis
   ↓
Visualization
   ↓
Correlation Analysis
   ↓
Linear Regression
   ↓
Model Evaluation
   ↓
Conclusions
```

## 💡 Key Takeaway

This project demonstrates a simple workflow for going from raw tabular data to meaningful observations and a basic machine-learning model.

More importantly, it serves as an introduction to using Python for **data analysis, visualization, and machine learning**.

## 🚀 Future Improvements

Possible extensions to the project include:

* Using a larger real-world dataset
* Performing more extensive statistical analysis
* Comparing multiple machine-learning algorithms
* Adding additional student-related variables
* Building an interactive dashboard
* Improving model evaluation using cross-validation

## 👨‍💻 Author

**Mehul Bansal**

This project was created as a learning project to explore the fundamentals of data analysis and machine learning.
