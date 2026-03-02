# Inferential-Statistics-Project
Applied inferential statistics to real-world datasets using Python. Implemented probability analysis, hypothesis testing, t-tests, and two-way ANOVA to derive business and healthcare insights.

# 📊 Inferential Statistics & Data Analysis Project

This repository contains a complete **Inferential Statistics project** implemented using **Python (Jupyter Notebook)** along with a detailed business interpretation report.

The project applies statistical theory to solve real-world problems across **sports analytics, manufacturing quality control, material science, and healthcare analytics**. The aim is to demonstrate how statistical inference can guide decision-making instead of relying on assumptions.

The analysis focuses on extracting insights using probability theory, hypothesis testing, and ANOVA techniques to support practical recommendations.

---

## 🎯 Project Objectives
The project answers four major applied statistical problems:

1. Analyze football player injury patterns
2. Evaluate packaging material strength (gunny bags)
3. Assess hardness suitability of stones for industrial printing
4. Study factors affecting dental implant hardness

The goal is to show how **data-driven statistical inference** can improve safety, quality control, and industrial processes.

---

## 🧠 Concepts Used

- Descriptive statistics
- Probability theory
- Normal distribution (Z-scores & CDF)
- Hypothesis testing (t-tests)
- Confidence reasoning
- ANOVA (one-way and two-way)
- Interaction effects
- Outlier treatment (IQR & percentile methods)
- Data visualization (histograms & boxplots)
- Decision-based statistical interpretation

---

## 🗂 Repository Structure

├── is coded project.ipynb # Jupyter notebook containing all analysis
├── is coded business report.pdf # Business interpretation & conclusions
└── README.md # Project documentation
---

## ⚙️ Technologies Used

- Python 3
- Jupyter Notebook
- NumPy
- Pandas
- SciPy
- Matplotlib
- Seaborn
- Statsmodels

---

## 📌 Problem Statements & Analysis

### 1️⃣ Football Injury Probability Analysis
A physiotherapist studied whether **player position affects foot injury risk**.

Key findings:
- Probability of injury ≈ **61.7%**
- Probability player is forward/winger ≈ **52.3%**
- Probability a striker is injured ≈ **19.1%**
- Probability an injured player is a striker ≈ **31%**

**Insight:**  
Certain playing positions show higher injury risk, suggesting targeted training and preventive physiotherapy programs.

---

### 2️⃣ Gunny Bag Strength (Quality Control)

The breaking strength of cement packaging bags follows a **normal distribution**  
Mean = 5 kg/cm²  
Standard deviation = 1.5 kg/cm²

Results:
- 11.2% bags are weaker than required
- 82.5% meet acceptable strength
- 13.9% fall outside safe operating range

**Insight:**  
Manufacturing quality checks are necessary to prevent material loss and supply chain damage.

---

### 3️⃣ Stone Hardness for Printing

Industrial printing requires **Brinell hardness ≥ 150**.

A one-sample t-test showed:
- Mean hardness of unpolished stones ≈ 134
- Statistically significant difference

**Conclusion:**  
Unpolished stones are **not suitable** for precision printing.

Polished stones were significantly harder than unpolished stones.

---

### 4️⃣ Dental Implant Hardness (ANOVA Study)

Factors tested:
- Dentist
- Method
- Alloy
- Temperature

Results:
- No significant difference among dentists
- Some methods significantly affect hardness
- Interaction effect present for Alloy-1 but not Alloy-2

**Insight:**  
Implant success depends more on **method and material** than on the individual dentist.

---

## 📊 Key Learnings

This project demonstrates:

- Statistical testing prevents incorrect conclusions
- Quality control benefits from probability modeling
- Material treatment improves industrial reliability
- Healthcare outcomes can be optimized using ANOVA-based evaluation

---



## 🚀 How to Run the Project

2. Install dependencies
pip install pandas numpy matplotlib seaborn scipy statsmodels jupyter
3. Launch notebook
jupyter notebook
4. Open
is coded project.ipynb

📈 Final Conclusion

The project shows how inferential statistics bridges mathematics and real-world decision making.
Instead of guessing, organizations can use statistical evidence to:

reduce injuries

improve manufacturing reliability

ensure industrial material suitability

optimize healthcare treatment processes

👤 Author

Sham Solanki
Master’s in Data Science & Business Analytics


### 1. Clone the repository
```bash
git clone https://github.com/yourusername/inferential-statistics-project.git
cd inferential-statistics-project
