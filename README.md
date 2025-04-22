This project explores the **effect of morphine dosage on pain perception** using a randomized block design and statistical modeling in R.

## Objective

Investigate whether increasing levels of morphine significantly change a participant’s pressure pain threshold using simulated patient data from the *Islands* platform.

---

## 📊 Study Summary

- **Design**: Randomized Block Design
- **Factors**: Dosage (0mg, 20mg, 40mg, 60mg)
- **Blocks**: Gender (2 levels) and Age Group (3 levels)
- **Sample Size**: 192 participants
- **Response Variable**: Pain threshold before and after morphine treatment

---

## 🔍 Methods

- Two-Way ANOVA using `aov()` in R
- Tukey’s HSD for post-hoc comparisons
- Boxplots and residual diagnostic plots
- Power analysis conducted using G*Power

---

## 📈 Key Findings

- No statistically significant differences in pain tolerance across morphine dosage levels
- Neither **age** nor **gender** showed a significant effect
- Diagnostic plots revealed some non-normality and heteroscedasticity
- Results suggest caution when interpreting the ANOVA output due to these violations

---

## 🧪 Tools Used

- **R**: `dplyr`, `ggplot2`, `stats`, `base`
- **G*Power**: for statistical power analysis
