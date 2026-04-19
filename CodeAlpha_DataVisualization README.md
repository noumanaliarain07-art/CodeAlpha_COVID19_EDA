# 📊 COVID-19 Mexico — Data Visualization

> **CodeAlpha Data Analytics Internship | Task 3**

[![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)](https://pandas.pydata.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange)](https://matplotlib.org/)
[![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Plots-4c72b0)](https://seaborn.pydata.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter)](https://jupyter.org/)

---

## 👤 Author

**Nouman Ali Arain**
Student — IT/CS Department, SBBU Nawabshah
Data Analytics Intern @ [CodeAlpha](https://www.codealpha.tech/)
GitHub: [@noumanaliarain07-art](https://github.com/noumanaliarain07-art)
LinkedIn: [nouman-ali-0534a2398](https://linkedin.com/in/nouman-ali-0534a2398)

---

## 📌 Project Overview

This project is **Task 3** of my CodeAlpha Data Analytics Internship.
It builds on the EDA done in Task 2 and focuses entirely on **visual storytelling** with the COVID-19 Mexico dataset.

8 different chart types are used to uncover patterns related to:
- Patient demographics (age, gender)
- Clinical outcomes (death, hospitalization)
- Comorbidity prevalence
- Risk factor correlations

---

## 📂 File Structure

```
CodeAlpha_COVID19_EDA/
├── CodeAlpha_DataVisualization_new.ipynb   # Main notebook (Task 3)
├── EDA_Code.py                             # EDA script (Task 2)
├── DataVisualization_Code.py               # Visualization script (Task 3)
├── Covid Data.csv                          # Dataset (not included — see below)
└── README.md
```

> ⚠️ The dataset (`Covid Data.csv`) is not included in this repo due to file size.
> You can download it from [Kaggle — COVID-19 Mexico Dataset](https://www.kaggle.com/).

---

## 📊 Visualizations Created

| # | Chart Type | Topic |
|---|-----------|-------|
| 1 | Bar Chart | Patient Type Distribution (Ambulatory vs Hospitalized) |
| 2 | Pie Chart | Gender Distribution |
| 3 | KDE Plot | Age Distribution — Survived vs Died |
| 4 | Horizontal Bar | Death Rate by Age Group |
| 5 | Horizontal Bar | Comorbidity Prevalence (Diabetes, Hypertension, Obesity, etc.) |
| 6 | Bar Chart | Death Rate by Gender |
| 7 | Heatmap | Correlation Matrix — Risk Factors |
| 8 | Stacked Bar | Hospitalization Rate by Age Group |

---

## 🔍 Key Insights

- 🏥 **Most patients were ambulatory** (mild/outpatient cases)
- 👴 **75+ age group** shows the highest mortality rate
- 💉 **Pneumonia and intubation** are most strongly correlated with death
- 🫀 **Hypertension and Diabetes** are the most common comorbidities
- ♂️ **Males** have a slightly higher death rate than females
- 📈 **Hospitalization rate increases sharply** after age 60

---

## 🛠️ Tools & Libraries

| Library | Purpose |
|---------|---------|
| `pandas` | Data loading and preprocessing |
| `numpy` | Numerical operations |
| `matplotlib` | Core chart plotting |
| `seaborn` | Statistical visualizations & theming |

---

## ▶️ How to Run

1. Clone the repository:
```bash
git clone https://github.com/noumanaliarain07-art/CodeAlpha_COVID19_EDA.git
cd CodeAlpha_COVID19_EDA
```

2. Install required libraries:
```bash
pip install pandas numpy matplotlib seaborn
```

3. Place `Covid Data.csv` in the project folder.

4. Update the dataset path in the notebook (Cell 2):
```python
df = pd.read_csv("Covid Data.csv", low_memory=False)
```

5. Open and run the notebook:
```bash
jupyter notebook CodeAlpha_DataVisualization_new.ipynb
```

---

## 🔗 Related Tasks

- **Task 1** — Data Cleaning & Preprocessing
- **Task 2** — Exploratory Data Analysis (EDA)
- **Task 3** — Data Visualization ✅ *(this repo)*

---

## 📜 License

This project is part of a learning internship and is open for educational use.

---

*Made with ❤️ by Nouman Ali Arain | CodeAlpha Internship 2024–2025*
