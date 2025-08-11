# 📈 [A/B Testing Project 2](https://github.com/DhawaDG/AB_Testing_Project/blob/main/README.md): Mobile App Install Button Optimization
---
## 🧪 Overview
This project evaluates whether a redesigned install button increases mobile app installations compared to the current design using Fisher's Exact Test for binary outcomes.
---
## 🗂️ Project Details
- **Project ID:** 2
- **Title:** Mobile App Install Button Optimization
- **Method:** Fisher's Exact Test
- **Data Type:** Binary (0 = No Install, 1 = Install)
- **Time Spent:** 2-3 hours
- **Difficulty Level:** Beginner
---
## 🎯 Objective
To determine if the redesigned install button increases conversion rates compared to the current button.
---
## 📊 Hypotheses
- **Null Hypothesis (H₀):** No difference in install rates between current and redesigned buttons
- **Alternative Hypothesis (H₁):** The redesigned button affects install rates
- **Type I Error Rate (α):** 0.05
- **Test Type:** Two-tailed (Fisher's Exact Test)
---
## 🧰 Tools & Libraries
- Python
- Pandas
- SciPy (for Fisher's Exact Test)
- Matplotlib (visualization)
---
## 📁 Dataset Structure
Simulated binary data:

| variant   | installed |
|-----------|-----------|
| control   | 1         |
| control   | 0         |
| ...       | ...       |
| treatment | 1         |
| treatment | 0         |

- **variant:** Either "control" (current) or "treatment" (redesigned)
- **installed:** 1 if installed, 0 if not
---
## 📈 Results
- Performed Fisher's Exact Test on 2×2 contingency table
- Calculated odds ratio to measure effect size

**Results:**
- Control conversion rate: 5.0%
- Treatment conversion rate: 7.5%
- Odds ratio: 1.541 (54.1% higher odds)
- p-value: 0.0263 (statistically significant)
---
## 📚 Key Concepts Learned
- Contingency table construction
- Fisher's Exact Test for small samples
- Odds ratio interpretation
- Binary outcome analysis
- Practical vs statistical significance
---
## 🔗 References
- [Trustworthy Online Controlled Experiments - Ron Kohavi](https://www.scribd.com/document/711189937/Kohavi-Diane-Tang-Xu-Trustworthy-Online-Controlled-Experiments-A-Practical-Guide-to-AB-Testing-2020)
- [Practical Statistics for Data Scientists](https://github.com/DhawaDG/Email-Newsletter-Signup-Optimization/blob/master/reference%20book/Practical%20Statistics%20for%20Data%20Scientists%20(%20PDFDrive%20).pdf)
- [SciPy Fisher's Exact Test documentation](https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.fisher_exact.html)
---
## 🚀 Next Steps
- Run test with larger sample sizes
- Calculate confidence intervals for odds ratio
- Test different button designs (colors, sizes, text)
- Implement Bayesian A/B testing approach
---
##  **📂[+20 AB Testing Projects →](https://github.com/DhawaDG/AB_Testing_Project/blob/main/README.md)** 
