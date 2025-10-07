# EDA_student-dataset-by-Syed
> ✅ This project was completed as part of the **Infosys Springboard Internship 6.0**, showcasing practical data analysis skills and real-world application of Python.


## 🧑‍💻 Author
**Syed Sharshad**  
Python Fullstack Developer | Data Analyst

# 🎓 Exploratory Data Analysis on Student Performance Dataset

This project focuses on performing **Exploratory Data Analysis (EDA)** on a student academic dataset to uncover meaningful insights about factors that influence students’ grades and performance.  
The goal is to understand trends, relationships, and patterns within the data — and to demonstrate the application of data analysis techniques using Python.

---

## 📘 Project Overview

The project involves analyzing student scores across multiple subjects, along with demographic and lifestyle factors such as **gender** and **part-time job status**.  

Through this analysis, we aim to answer questions like:
- How do students perform across different subjects?
- Do gender or part-time jobs impact academic performance?
- Which subjects are most correlated with overall grade?
- What patterns or relationships can we visualize from the data?

---

## 🧩 About the Dataset

The dataset contains academic information for a group of students.  
Each record represents one student’s scores across subjects along with their grade and background details.

| **Column Name** | **Description** |
|-----------------|-----------------|
| `math_score` | Score obtained in Mathematics |
| `physics_score` | Score obtained in Physics |
| `chemistry_score` | Score obtained in Chemistry |
| `biology_score` | Score obtained in Biology |
| `history_score` | Score obtained in History |
| `geography_score` | Score obtained in Geography |
| `english_score` | Score obtained in English |
| `gender` | Gender of the student (Male/Female) |
| `part_time_job` | Whether the student has a part-time job (Yes/No) |
| `grade` | Overall grade classification of the student |

**Dataset Type:** Tabular (Structured)  
**Number of Features:** ~10  
**Data Types:** Numerical and Categorical  

---

## 🧮 Data Preprocessing & Cleaning

The following preprocessing steps were performed:
1. **Handled missing values** — imputed with mean/median where appropriate.  
2. **Checked for duplicates** and removed redundant rows.  
3. **Converted data types** (e.g., categorical encoding where needed).  
4. **Created derived features** such as:
   - `total_score` – sum of all subject scores  
   - `percentage` – overall percentage  
   - `science_to_arts_ratio` – ratio of science subject average to arts subject average  
   - `high_achiever` – flag indicating students scoring above 75%

---

## 📊 Exploratory Data Analysis

The EDA was conducted using **Pandas**, **NumPy**, **Matplotlib**, and **Seaborn**.

Key steps and visualizations include:

- Distribution of grades and subject scores  
- Boxplots showing variation in grades by gender and part-time job status  
- Correlation heatmap among subjects  
- Pairplots to observe relationships between subjects  
- Grouped bar plots comparing average performance across categories  

Example visualizations:

```python
sns.boxplot(x='gender', y='percentage', data=df)
sns.heatmap(df.corr(), annot=True, cmap='coolwarm')

## 📢 About Me
I’m passionate about data analysis, Python development, and building real-world projects. This EDA is part of my growing portfolio to showcase practical skills and storytelling through data.

## 📬 Contact
Feel free to connect with me on:
- [LinkedIn](https://www.linkedin.com/in/syedsharshad)
- [GitHub](https://github.com/sd-sharshad)


