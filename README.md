# 🎓 Student Feedback Survey Analysis — Data Science & Analytics Project

This project analyzes student feedback collected from college courses to understand satisfaction levels, teaching effectiveness, and areas of improvement. Using Python, pandas, and visualization techniques, the project transforms raw numeric survey responses into meaningful insights and actionable recommendations.

---

## 📊 Project Overview

Colleges frequently collect feedback through surveys, but this data often remains unused.
In this project, we analyze a structured **Student Feedback Survey** dataset where students rate:

* Subject knowledge
* Clarity of explanation
* Presentation usage
* Assignment difficulty
* Doubt solving
* Course structure
* Extra support
* Course recommendation

Ratings are on a **1–10 scale**.

---

## 🧪 Objectives

This project aims to:

* Clean and prepare raw feedback data
* Compute average ratings for each question
* Calculate per-student satisfaction score
* Identify strengths and weaknesses
* Explore correlations between feedback factors
* Visualize student satisfaction trends
* Generate insights and recommendations for improvement

---

## 🗂 Dataset Description

The dataset contains ~1000 student responses with the following columns:

* `Student ID`
* `Well versed with the subject`
* `Explains concepts in an understandable way`
* `Use of presentations`
* `Degree of difficulty of assignments`
* `Solves doubts willingly`
* `Structuring of the course`
* `Provides support for students going above and beyond`
* `Course recommendation based on relevance`

All values range from **1–10**.

---

## 🛠 Tools & Libraries

This project is implemented in **Google Colab** using:

* **pandas** – data cleaning & analysis
* **matplotlib / seaborn** – data visualization
* **numpy** – numerical operations

---

## 📈 Key Steps Performed

### ✔ **1. Data Cleaning & Preparation**

* Removed unnamed index column
* Renamed long column names for easier use
* Checked for missing values and validated datatypes

### ✔ **2. Average Score per Question**

Identified best and worst rated aspects of teaching.

### ✔ **3. Student Satisfaction Score**

Calculated a combined satisfaction score for each student (mean of all ratings).

### ✔ **4. Visualizations**

* Bar charts
* Boxplots
* Correlation heatmap
* Satisfaction score distribution

### ✔ **5. Strengths & Weaknesses**

* **Strengths:** Subject knowledge, explanation clarity, presentation usage
* **Weaknesses:** Assignment difficulty, doubt solving support, course relevance

### ✔ **6. Correlation Analysis**

Found relationships between different feedback elements to identify high-impact areas.

---

## 🧠 Insights Summary

* Overall satisfaction: **5.92 / 10**
* Students appreciate **subject knowledge and clarity of explanations**
* Improvement needed in **assignment difficulty, doubt solving, and course relevance**
* Strong correlations show improving doubt-solving support can significantly raise satisfaction

---

## 📝 Recommendations

* Add more structured doubt-solving sessions
* Simplify assignments or improve guidance
* Connect course content to real-world applications
* Use more visual aids to maintain engagement
* Standardize course structure across instructors

---

## 📁 Project Deliverables

* ✓ Cleaned and well-commented **Jupyter Notebook / Colab Notebook**
* ✓ Visual charts (distribution, bar charts, heatmaps)

---
