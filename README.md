# OIBSIP_DataAnalytics_Task3
Systematic data cleaning and transformation pipeline using Pandas to handle missing values, duplicates, outliers, and formatting inconsistencies
## 📌 Objective
To demonstrate professional-level data cleaning skills by systematically inspecting a messy dataset, treating missing data, removing duplicates, standardizing inconsistent formats, and capping outliers.

---

## 🛠️ Tools & Tech Stack
- **Language:** Python
- **Environment:** Jupyter Notebook (Anaconda Distribution)
- **Libraries:** `pandas`, `numpy`, `seaborn`

---

## 📊 Steps Performed & Cleaning Strategy
1. **Quality Audit:** Produced a initial report on missing values, duplicate rows, and data type issues.
2. **Duplicate Removal:** Identified and dropped duplicate rows.
3. **Missing Data Imputation:** Applied median imputation for `age` and mode imputation for `embarked`.
4. **Standardization:** Normalized text casing/padding (`Male`/`Female`) and converted dates to standard `datetime64` format.
5. **Outlier Treatment:** Applied IQR Winsorization (capping) on numerical columns (`fare`, `age`) to preserve sample size while eliminating extreme skews.
6. **Export:** Produced a "Before vs. After" audit summary table and saved the cleaned dataset.

---

## 💡 Outcome
- Successfully transformed a messy dataset into an analysis-ready clean CSV with zero duplicate rows, zero missing values, standardized data types, and capped numeric outliers.
