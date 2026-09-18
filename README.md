# Employee Attrition Analysis

## 📌 Project Overview

Employee Attrition Analysis is a data analysis project that studies employee information to understand **employee status, gender, experience, age, hiring, termination, and retention**.

The project uses Python and data visualization to find useful patterns in employee data and understand how employee-related factors change over time.

---

## 🎯 Objectives

* Analyze active and terminated employees.
* Understand employee gender distribution.
* Analyze employee age and experience.
* Study hiring and termination trends over the years.
* Analyze employee retention.
* Understand termination types and reasons.
* Find relationships between age and experience.
* Identify patterns using charts and statistical analysis.

---

## 🛠️ Technologies Used

* **Python**
* **Pandas** – Data handling and analysis
* **NumPy** – Numerical operations
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical charts
* **Jupyter Notebook**

---

## 📂 Project Structure

```text
Employee-Attrition-Analysis/
│
├── Attrition copy.ipynb
├── dataset.csv
└── README.md
```

> Replace `dataset.csv` with the actual name of your dataset if it has a different name.

---

## 🔍 Analysis Performed

### 1. Employee Status Analysis

Analyzed the number of employees based on their status.

* Compared active and terminated employees.
* Most employees in the dataset are active.

### 2. Gender Analysis

Analyzed the distribution of employees by gender.

* Compared male and female employees.
* The workforce is almost balanced, with a slight difference between the two groups.

### 3. Experience Analysis

Analyzed employee experience using:

* Histogram
* KDE plot
* Average experience by employee status and gender

The experience distribution shows that many employees have around **13–14 years of experience**.

### 4. Hiring and Termination Analysis

Studied hiring and termination trends over different years.

* Compared the number of employees hired and terminated.
* The notebook shows the highest hiring around **1998** and high termination around **2014**.

### 5. Retention Analysis

Analyzed how employee retention changes over the years.

* Compared retention across different years.
* The notebook shows high retention around **2013**.

### 6. Termination Analysis

Analyzed:

* Termination type
* Termination reason

This helps understand the different reasons and types of employee termination.

### 7. Service Category Analysis

Compared employee status across service categories and gender.

* Active and terminated employees were compared.
* The analysis shows differences between service categories.

### 8. Age Analysis

Analyzed employee age using:

* Histogram
* KDE plot
* Box plot

The age distribution was studied to understand the age range of employees.

### 9. Age and Experience Relationship

Used scatter plots and joint plots to compare **age and experience**.

The analysis shows that older employees generally have more work experience.

### 10. Correlation Analysis

A correlation heatmap was used to understand the relationship between numerical columns.

The analysis shows a strong positive relationship between **age and experience**.

### 11. Pair Plot Analysis

A pair plot was used to compare relationships between different numerical columns and identify patterns in the data.

---

## 📊 Visualizations

The project includes the following charts:

* Employee Status Count Plot
* Gender Distribution Pie Chart
* Average Experience by Gender and Status
* Hiring and Termination Trend
* Retention Trend
* Termination Type Distribution
* Termination Reason Distribution
* Service Category by Gender and Status
* Experience Histogram
* Experience KDE Plot
* Employee Age Distribution
* Age KDE Plot
* Age vs Experience Scatter Plot
* Age vs Experience Joint Plot
* Correlation Heatmap
* Pair Plot
* Box Plot

---

## 💡 Key Findings

* Most employees are **active** compared with terminated employees.
* The workforce is almost balanced between male and female employees.
* Many employees have around **13–14 years of experience**.
* Hiring and termination numbers change across different years.
* The analysis shows high hiring around **1998** and high termination around **2014**.
* Age and experience generally increase together.
* The analysis shows a strong relationship between age and experience.

---

## 🚀 How to Run the Project

### Step 1: Clone the Repository

```bash
git clone https://github.com/yourusername/Employee-Attrition-Analysis.git
```

### Step 2: Open the Project

```bash
cd Employee-Attrition-Analysis
```

### Step 3: Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### Step 4: Start Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
Attrition copy.ipynb
```

Run the notebook cells to view the complete analysis.

---

## 📈 Project Outcome

This project helped analyze employee data using Python and understand important patterns related to **employee attrition, age, experience, hiring, termination, and retention**.

It demonstrates practical skills in **data cleaning, data analysis, visualization, and exploratory data analysis (EDA)**.

---

## 👨‍💻 Author

**Anand Rathod**

Aspiring Data Analyst | Python | SQL | Power BI | Data Science

---

## ⭐ Future Improvements

* Build an interactive Power BI dashboard.
* Add more employee-level analysis.
* Create an employee attrition prediction model using Machine Learning.
* Add additional business insights from the dataset.
