# Statistical Tests Practice 📊

A collection of practical data analysis and hypothesis testing projects using Python and real-world datasets.

This repository demonstrates the application of fundamental statistical concepts and tests used in data analysis to answer business and analytical questions.

---

## 📌 Project Overview

The notebooks in this repository cover:

- Z-Score
- Z-Test
- One-Sample T-Test
- Two-Sample T-Test
- Paired T-Test concepts
- Chi-Square Test
- ANOVA
- Central Limit Theorem
- Hypothesis Testing
- P-Value interpretation
- Null and Alternative Hypotheses
- Type I and Type II Errors

Each notebook applies statistical concepts to practical datasets and interprets the results in a data analysis context.

---

## 📂 Repository Structure

### 1️⃣ Central Limit Theorem and One-Sample T-Test

**Files:**

- `Central_Limit_Theoram_and_T-test-One_Sample.ipynb`
- `Central_Limit_Theoram_and_T-test-One_Sample.pdf`

Topics covered:

- Central Limit Theorem (CLT)
- Sampling distributions
- Sample mean vs population mean
- One-Sample T-Test
- Null and Alternative Hypotheses
- P-Value interpretation
- Type I and Type II Errors

**Business Question Example:**

> Is the average value of a sample significantly different from a known or expected population value?

---

### 2️⃣ Chi-Square Test and ANOVA

**Files:**

- `Chi_SquareTest_and_AnovaTest.ipynb`
- `Chi_SquareTest_and_AnovaTest.pdf`

Topics covered:

- Chi-Square Test of Independence
- Chi-Square Goodness-of-Fit
- One-Way ANOVA
- Categorical vs Numerical variables
- Comparing multiple groups
- Statistical significance

**Business Question Examples:**

> Is there a significant relationship between two categorical variables?

> Do the average values differ significantly across multiple groups?

---

### 3️⃣ Z-Test vs T-Test – Uber Dataset

**Files:**

- `Z_Test_VS_T_Test_Uber_Dataset.ipynb`
- `Z_Test_VS_T_Test_Uber_Dataset.pdf`

Topics covered:

- Z-Test
- Two-Sample T-Test
- Comparing group means
- Sample size considerations
- Population variance and standard deviation concepts
- Hypothesis testing and p-values

**Business Question Example:**

> Is there a statistically significant difference in booking values between two pickup locations?

---

### 4️⃣ Z-Score vs Z-Test – JP Morgan Dataset

**Files:**

- `JP_Morgan_ZScore_VS_ZTest.ipynb`
- `JP_Morgan_ZScore_VS_ZTest.pdf`

Topics covered:

- Z-Score calculation
- Identifying unusual observations
- Standardization
- Z-Test
- Difference between Z-Score and Z-Test

**Key Concept:**

> A Z-Score measures how far an individual observation is from the mean, while a Z-Test is used to test whether a sample statistic differs significantly from a population parameter or another sample.

---

## 🧪 Statistical Test Selection Guide

| Test | Variable Types | Number of Groups | Example Question |
|---|---|---:|---|
| **One-Sample T-Test** | Numerical vs known value | 1 | Is the average delivery time different from 30 minutes? |
| **Two-Sample T-Test** | Categorical + Numerical | 2 | Is average booking value different between Auto and Bike? |
| **Paired T-Test** | Two related numerical measurements | Same subjects | Did customer satisfaction change before vs after an improvement? |
| **ANOVA** | Categorical + Numerical | 3+ | Does average booking value differ across multiple locations? |
| **Chi-Square** | Categorical + Categorical | 2+ | Is flight status associated with airline? |
| **Correlation** | Numerical + Numerical | N/A | Is ride distance related to booking value? |
| **Z-Test** | Numerical or proportion | 1 or 2 | Is the difference between two large samples statistically significant? |

---

## 🔬 General Hypothesis Testing Workflow

The notebooks generally follow this process:

### 1. Define the Business Question

Example:

> Is the average booking value different between two locations?

### 2. Define Hypotheses

**Null Hypothesis (H₀):**

> There is no statistically significant difference.

**Alternative Hypothesis (H₁):**

> There is a statistically significant difference.

### 3. Choose the Appropriate Statistical Test

The test depends on:

- Variable type
- Number of groups
- Whether samples are independent or paired
- Sample size
- Population variance information

### 4. Calculate the Test Statistic and P-Value

Examples include:

- T-statistic
- Z-statistic
- Chi-Square statistic
- F-statistic

### 5. Interpret the Results

Using a significance level of:

```text
α = 0.05


**Author** Ratnajit Chakraborty
https://www.linkedin.com/in/ratnajit-chakraborty-076ab520a
