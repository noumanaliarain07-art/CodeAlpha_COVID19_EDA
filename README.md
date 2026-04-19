# 🦠 COVID-19 Mexico — Exploratory Data Analysis (EDA)

**Internship:** CodeAlpha | **Task:** Task 2  
**Author:** Nouman Ali Arain | SBBU Nawabshah

---

## 📌 Project Overview

This project performs a detailed Exploratory Data Analysis (EDA) on the COVID-19 Mexico dataset. The goal is to uncover meaningful patterns related to patient mortality, age, gender, and comorbidities using Python.

---

## ❓ Research Questions

1. What is the overall death rate of COVID-19 patients in Mexico?
2. Does age play a significant role in patient mortality?
3. Which comorbidities (Diabetes, Hypertension, etc.) increase death risk?
4. Is there a difference in death rate between male and female patients?
5. What percentage of patients were hospitalized vs ambulatory?
6. Are there any outliers or anomalies in the age data?
7. Is there missing or inconsistent data that needs to be handled?
8. Does pneumonia presence increase the risk of death?

---

## 📁 Dataset

- **File:** `Covid Data.csv`
- **Original Shape:** 1,048,575 rows × 21 columns
- **After Removing Duplicates:** 236,526 rows × 21 columns
- **Source:** Mexican Government COVID-19 public dataset

---

## 🛠️ Libraries Used

```python
pandas | numpy | matplotlib | seaborn | scipy
```

---

## 🔍 Analysis Steps

| Step | Description |
|------|-------------|
| 1 | Import Libraries |
| 2 | Load Dataset |
| 3 | Data Structure & Types |
| 4 | Statistical Summary |
| 5 | Missing Value Check |
| 6 | Duplicate Removal |
| 7 | Feature Engineering (`DIED`, `GENDER`, `AGE_GROUP`) |
| 8 | Age Distribution (Histogram) |
| 9 | Gender Distribution (Bar Chart) |
| 10 | Death Rate by Age Group |
| 11 | Comorbidities vs Death Rate |
| 12 | Correlation Heatmap |
| 13 | Outlier Detection (IQR + Boxplot) |
| 14 | Hypothesis Testing (T-Test: Age vs Death) |
| 15 | EDA Summary |

---

## 📊 Key Results

| Metric | Value |
|--------|-------|
| Total Records | 236,526 |
| Total Deaths | 30,103 |
| Death Rate | 12.73% |
| Mean Age | 52.6 years |
| Age Outliers (IQR) | 37 |

---

## 💡 Key Insights

- **Age matters:** Patients aged 60+ have a significantly higher death rate (~17–18%)
- **Comorbidities:** Diabetes and Hypertension are the top risk factors
- **Pneumonia:** Strongly linked to patient mortality (death rate ~20% with pneumonia)
- **Gender:** Males have a slightly higher death rate than females
- **Hypothesis Test:** T-Test confirms age significantly affects death (p-value ≈ 0.0000)

---

## 📂 File Structure

```
CodeAlpha_COVID19_EDA/
│
├── Covid Data.csv               # Raw dataset
├── CodeAlpha_EDA_Task2.ipynb    # Jupyter Notebook (EDA)
├── CodeAlpha_EDA_Task2.py       # Python script version
└── README.md                    # Project documentation
```

---

## 🚀 How to Run

```bash
# 1. Clone the repository
git clone https://github.com/noumanaliarain07-art/CodeAlpha_COVID19_EDA.git

# 2. Install dependencies
pip install pandas numpy matplotlib seaborn scipy

# 3. Run the notebook
jupyter notebook CodeAlpha_EDA_Task2.ipynb
```

---

## 🙋‍♂️ Author

**Nouman Ali Arain**  
IT/CS Student — SBBU Nawabshah  
Python Development & Data Analytics Intern — CodeAlpha  

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue)](https://linkedin.com/in/nouman-ali-0534a2398)  
[![GitHub](https://img.shields.io/badge/GitHub-Profile-black)](https://github.com/noumanaliarain07-art)
