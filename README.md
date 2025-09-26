# INL2 R Analysis — IDE Efficiency Experiment

This repository contains R code and outputs for the **DVA463 Research Methods (INL2 Scenario 1)** assignment.  
The analysis investigates which of two IDEs (IDE-A vs IDE-B) improves developer efficiency, based on experimental data with 10 programmers.

---

## 🔎 Analysis Steps
1. **Descriptive statistics**  
   - Computed mean, median, SD, IQR, min, max for Prog-1 and Prog-2.  
   - Checked paired differences (IDE-A − IDE-B).

2. **Visualisations**  
   - **Box plot**: Prog-1 vs Prog-2 development times.  
   - **Scatter plot**: Programmer-level comparison with line of equality (y=x).  
   - **Histogram**: Paired differences distribution.  
   - **Bar plot**: Per-programmer side-by-side comparison.  
   - **Bell curves**: Normal curve overlays for visualising distributional shape.

3. **Hypothesis testing**  
   - Paired **t-test** (parametric), \(H_0: \mu_A = \mu_B\).  
   - Obtained **t = -1.239, p = 0.247 (df=9)**.  
   - 95% CI: [−28.23, 8.25].  
   - Decision: **Fail to reject H₀** → no significant difference in mean times.

---

## 📊 Key Results
- IDE-B was on average **~10 minutes faster** than IDE-A.  
- But variability was high, and the difference was **not statistically significant**.  
- With this sample (n=10), **we cannot confidently recommend one IDE over the other**.  
- A larger sample and stricter experimental control would improve reliability.

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/aslsumen/inl2-r-analysis.git
