# ♟️ Statistical Analysis of Chess Games (R Project)

![R](https://img.shields.io/badge/R-276DC3?logo=r\&logoColor=white)
![Statistics](https://img.shields.io/badge/Statistics-Descriptive%20%26%20Inferential-orange)
![Data Visualization](https://img.shields.io/badge/Data%20Visualization-ggplot2-brightgreen)
![License](https://img.shields.io/badge/License-MIT-yellow)

A comprehensive **statistical exploration of chess games** using the **R programming language**, uncovering insights into player ratings, game dynamics, opening strategies, and victory conditions.

---

## 🚀 Project Overview

The goal of this project is to apply a wide range of **statistical methods** to a dataset of chess games (`games.csv`) in order to extract insights and test hypotheses.

The analysis covers:

* 🔹 **Data Preprocessing** → Cleaning and preparing raw chess game data.
* 🔹 **Systematic Sampling** → Building a representative dataset sample.
* 🔹 **Descriptive Statistics** → Summarizing data distributions and trends.
* 🔹 **Inferential Statistics** → Hypothesis testing, confidence intervals, regression models.
* 🔹 **Non-parametric Tests** → Handling cases where assumptions of parametric tests don’t hold.

All results are documented in the **`code.R`** script and summarized in the **`Report.pdf`**.

---

## 📂 Files

* **`code.R`** → Main R script (data cleaning, sampling, tests, modeling).
* **`games.csv`** → Dataset of chess games.
* **`Report.pdf`** → Summary of findings and conclusions.

---

## 📊 Statistical Methods

The `code.R` script applies a diverse set of statistical techniques:

### 📈 Data Visualization

* Histograms, bar plots, box plots, scatter plots.

### 📏 Estimation

* Means, standard deviations, and **confidence intervals**.

### 🧪 Hypothesis Testing

* **t-tests** → Compare mean number of turns (e.g., rated vs unrated).
* **Proportion Tests** → Compare win proportions of white vs black.
* **Chi-squared Tests** → Goodness-of-fit, independence, homogeneity.

### 📉 Regression Analysis

* **Simple Linear Regression** → Player rating vs opponent rating, game length vs number of turns.
* **Logarithmic Transformations** for model linearization.

### 📊 ANOVA

* **One-way ANOVA** → Turns across different victory statuses.
* **Two-way ANOVA** → Interaction between winner and rated status.

### ⚖️ Non-parametric Tests

* **Wilcoxon Rank-Sum Test** → Alternative to t-test.
* **Spearman’s Rank Correlation** → Monotonic relationships.
* **Runs Test** → Randomness check.

---

## ▶️ How to Run

1. **Install R & RStudio** (recommended).
2. **Install required libraries**:

   ```R
   install.packages(c("tidyr", "ggplot2", "dplyr", "stringr", 
                      "DescTools", "corrplot", "BSDA", "randtests"))
   ```
3. **Set working directory**: Update the file path in `code.R` (currently `/Downloads/games.csv`) to your local dataset path.
4. **Run the script**: Execute `code.R` in RStudio (top to bottom) to perform the full analysis.

---

## 🔑 Key Findings (from the analysis)

* Rated vs. unrated games show **significant differences** in length and outcomes.
* **White vs. Black win proportions** are tested for statistical significance.
* **Regression models** predict player rating from opponent rating and turns from game length.
* **Victory type (checkmate, resignation, draw, etc.)** influences average game length.

---

## 👥 Contributors

This project was made possible thanks to the efforts of the following contributors:

* 🧑‍💻 \[Briksam Kasımoğlu]
* 🧑‍💻 \[Firas Elbayoumi]
* 🧑‍💻 \[Yaser Z. K. Shoshaa]
---
