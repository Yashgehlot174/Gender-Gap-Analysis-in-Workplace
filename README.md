<!-- Aesthetic GitHub README -->

<p align="center">
  <img src="https://img.shields.io/badge/Gender%20Gap%20Analysis-Data%20Science%20Project-pink?style=for-the-badge" />
</p>

<h1 align="center">💼 Gender Gap Analysis in the Workplace (1981–2013)</h1>
<p align="center">A visually rich data science project exploring factors behind the gender pay gap</p>

---

## 🌸 Overview
This project analyzes **U.S. workforce data from 1981–2013** to understand how factors such as  
**education, marital status, occupation, age, working hours**, and **experience** contribute to the  
persistent **gender wage gap**.

🧠 Techniques used:
- Regression Analysis (Linear + Logistic)
- Hypothesis Testing (T-test)
- PCA (Dimensionality Reduction)
- Extensive Data Visualization

---

## ✨ Key Highlights

### 📊 Persistent Pay Gap Across Categories
Visualizations show men consistently earn more across:
- Education levels  
- Occupations  
- Marital statuses  
- Age groups  
- Working hours  

### 🧪 Statistical Findings
- T-test → **p-value = 0.0**, confirming significant wage difference  
- Logistic Regression → **AUC ≈ 0.74** (moderate separability of gender)  
- Linear Regression → struggles with high-income outliers  

### 📉 Long-Term Trend
- Gender income gap slowly declining  
- Projected to reach *near zero around 2072*  

---

## 🗂 Repository Structure
```
├── README.md
├── Main.ipynb
├── Report.pdf
├── Dataset.csv
```

---

## 🔧 How to Run Locally

```bash
git clone https://github.com/Yashgehlot174/Gender-Gap-Analysis-in-Workplace.git
cd Gender-Gap-Analysis-in-Workplace
jupyter notebook Main.ipynb
```

---

## 📝 Features Analyzed
| Feature | Description |
|--------|-------------|
| **Sex** | Male/Female |
| **Educ99** | Education level |
| **Occ** | Occupation |
| **Incwage** | Yearly income |
| **Wkswork1** | Weeks worked/year |
| **Uhrswork** | Hours worked/week |
| **Marst** | Marital status |

---

## 🌈 Aesthetic Visual Summary
```
💰 Income Gap → Present in all categories
🎓 Education → Higher degree = higher pay, but gap persists
💼 Occupations → Some fields show drastic differences
👨‍👩‍👧 Marital Status → Married men show highest income advantage
⏳ Age → Gap widens with age, peaks at 50–60
```

---

## 🌟 Future Enhancements
- Add non-linear models (SVM, Random Forests, XGBoost)
- Add dashboards using Streamlit/PowerBI
- Explore fairness-aware ML algorithms
- Extend analysis to modern datasets (2014–2024)

---




---

<p align="center">
  Made with ❤️ for Data Science & Social Awareness
</p>


