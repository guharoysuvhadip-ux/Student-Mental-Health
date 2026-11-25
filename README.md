# 🧠 Student Mental Health Analysis

![Python](https://img.shields.io/badge/Python-3-blue?logo=python&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-data%20cleaning-150458?logo=pandas&logoColor=white)
![matplotlib](https://img.shields.io/badge/matplotlib-charts-11557c)
![seaborn](https://img.shields.io/badge/seaborn-visualisation-4c72b0)
![Colab](https://img.shields.io/badge/Google%20Colab-notebook-F9AB00?logo=googlecolab&logoColor=white)

## 📌 Overview
A data analysis project in a Google Colab notebook. It looks at a **student mental-health survey** of **101 responses** collected in **July 2020**, and explores how common depression, anxiety and panic attacks are among students and how they relate to gender, year of study and grades.

## 📂 Dataset
Source file: `Student Mental health.csv` (11 columns)

| Column | Description |
|---|---|
| ⏰ Timestamp | When the response was submitted |
| 🚻 Gender | Female / Male |
| 🎂 Age | 18 to 24 |
| 📚 Course | Free text (49 different spellings) |
| 🎓 Year of study | Year 1 to 4 |
| 📊 CGPA | Grade band |
| 💍 Marital status | Yes / No |
| 😔 Depression, 😰 Anxiety, ⚡ Panic attack | Yes / No |
| 🩺 Sought specialist treatment | Yes / No |

## 🧹 Part 1: Data Cleaning
1. 📥 Load the CSV with **pandas**
2. 🔍 Inspect with `head()`, `tail()`, `info()`, `describe()`, `dtypes`, `nunique()`
3. 👯 Check duplicates (**0 found**)
4. ❓ Check missing values (**1 missing Age**)
5. 🗑️ Drop the incomplete row, leaving **100 rows**
6. 💾 Save as `cleaned_data.csv`

> Course names and year-of-study spellings are not standardised in this notebook.

## 📈 Part 2: Data Visualization
Built with **matplotlib** and **seaborn**:
- 📊 Age distribution (histogram)
- 🥧 Gender split (pie chart)
- 🏫 Students per year of study, by gender
- 😰😔 Anxiety vs depression
- 🚻 Anxiety by gender, depression by gender
- 🎓 Anxiety by study year, depression by study year
- 📉 Panic attacks by CGPA band

## 💡 What the Data Shows
- 👩 **75%** of respondents are women, **25%** are men
- 😔 **35%** report depression, 😰 **34%** anxiety, ⚡ **33%** panic attacks
- 🩺 Only **6 students** sought specialist treatment
- 📅 Year 1 has the most respondents (42)

## 🚀 How to Run
1. Open `Student_Mental_Health.ipynb` in [Google Colab](https://colab.research.google.com/)
2. Upload `Student Mental health.csv` when prompted
3. Run all cells

## ⚠️ Limitations
Small, self-reported sample (not a clinical diagnosis). Results show association, not cause. Groups with fewer than 10 students should be read with caution.

## 🛠️ Built With

🐍 Python · 🐼 pandas · 📉 matplotlib · 🎨 seaborn · ☁️ Google Colab

## 📊 Dashboard

<img width="1520" height="2720" alt="dashboard_full" src="https://github.com/user-attachments/assets/c5aacdca-4a16-44bf-9d16-520eaa87c1f4" />











