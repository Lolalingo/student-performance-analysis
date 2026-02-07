# 🎓 Student Performance Analysis using Python

## 📌 Project Overview
This project explores the factors that influence students’ academic performance using Python.  
The goal is to understand how study time, absences, and other factors affect final grades and to practice real-world data analysis skills.

This project demonstrates data cleaning, exploratory data analysis (EDA), visualization, and insight generation using Python.

---

## 📂 Dataset Description
The dataset contains information about secondary school students, including academic performance and behavioral factors.

### Key Columns Used:
- **studytime** – Weekly study time (1 = low, 4 = high)
- **absences** – Number of school absences
- **G3** – Final grade (target variable)

---

## 🛠 Tools & Technologies
- Python  
- Pandas  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## 🔍 Data Analysis Steps

### 1. Data Loading
The dataset was imported using Pandas and explored using `.head()` and `.info()` to understand its structure.

### 2. Data Cleaning
- Checked for missing values using `isnull().sum()`
- Checked for duplicate records
- Verified data types and summary statistics

No missing values or duplicates were found in the dataset.

### 3. Exploratory Data Analysis (EDA)
- Descriptive statistics were generated using `describe()`
- Grouped analysis was performed to compare study time and final grades

### 4. Data Visualization
Several visualizations were created to understand relationships in the data:

- **Histogram** of final grades to understand grade distribution  
- **Violin Plot** of final grades by study time to observe grade variation  
- **box Plot** of absences vs final grade to examine correlation
- **bar chart** of average Final Grade by Study Time

---

## 📈 Key Findings

- Students who studied more generally achieved higher final grades.
- Higher absences were associated with lower academic performance.
- Grade distributions varied across different study time levels, showing performance differences among student groups.

---

---

## 🚀 Future Improvements
- Build a predictive model to forecast student grades
- Create an interactive dashboard using Power BI or Tableau
- Add correlation heatmaps and regression analysis
- Perform feature engineering for deeper insights

---
**created by lola**
## 📁 Project Structure

