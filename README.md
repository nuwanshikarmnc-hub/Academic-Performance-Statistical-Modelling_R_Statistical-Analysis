# Academic Performance Modeling  |  Factors Influencing Student Mathematics Performance

Impact of Academic and Lifestyle Factors on Student Final Mathematics Grades

**STAT 31631 - Statistical Modelling**  
*Department of Statistics & Computer Science, University of Kelaniya*

---

## 📌 Project Overview
This academic project investigates the determinants of students' final Mathematics grades (G_3) using the UCI Student Performance dataset (n = 649 records) originally collected by Cortez and Silva (2008). The study evaluates how prior academic performance (G_1, G_2), demographic characteristics, family background, and lifestyle factors collectively influence final outcomes.

## 🛠️ Tools & Data Sources
* **Tools:** R | MS Excel | UCI Machine Learning Repository

## 📊 Methodology & Key Findings
* **Variable Selection:** Forward, backward, and stepwise selection procedures were applied, all converging on a stable multiple linear regression (MLR) model.
  
* **Model Diagnostics:** Initial fitted models showed strong explanatory power (R^2 = 0.8547), but formal diagnostic tests revealed significant assumption violations (Shapiro-Wilk test for non-normality, Breusch-Pagan test for heteroscedasticity, and Durbin-Watson test for autocorrelation).
* **Response Transformations:** Square-root, cube-root, logarithmic, and Box-Cox transformations were investigated. While the Box-Cox transformation improved homoscedasticity and raised the R^2 to 0.8853, it still failed to resolve non-normality and independence issues.
* **Conclusion:** The study concludes that standard multiple linear regression is not entirely adequate for this dataset, emphasizing that high explanatory power (R^2) alone does not validate a model without rigorous assumption checking.

## 📂 Repository Structure
* `Final_Report.pdf` — academic report containing descriptive statistics, R outputs, residual plots, and diagnostic tables.
* `cleaned_R_analysis_dataset.xlsx` — Student Performance dataset used for the analysis
  
