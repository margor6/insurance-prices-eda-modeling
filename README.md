# Medical Insurance Prices - EDA & Econometric Modeling

![R](https://img.shields.io/badge/R-4.0%2B-blue)
![RMarkdown](https://img.shields.io/badge/Document-RMarkdown-orange)
![Status](https://img.shields.io/badge/Status-Completed-success)

## Overview

This project combines Exploratory Data Analysis (EDA) and econometric modeling of medical insurance prices using **RMarkdown**. The goal was to investigate how factors like age, BMI, and smoking status affect insurance charges, and to build a statistical model to explain and predict these costs.

The analysis discovers significant correlations and concludes with a linear regression model tailored to the underlying pricing mechanics.

## Dataset

The analysis uses the medical charges dataset, which contains data for **1,338 people**.

**Dataset's Columns:**
* `age`: Age of the person.
* `sex`: Person's gender (female, male).
* `bmi`: Body mass index.
* `children`: Number of children covered by health insurance.
* `smoker`: Smoking status.
* `region`: The person's residential area in the US.
* `charges`: Individual costs billed by health insurance.

## Tech
* **Core:** R 
* **Libraries:** `tidyverse`, `ggplot2`, `psych`, `mice`, `corrplot`, `gridExtra`, `nortest`, `car`, `PMCMRplus`, `lmtest`, `broom`.
* **Format:** RMarkdown report generated to HTML.

## Key Findings
* **Smoking Impact:** Being a smoker is the strongest single predictor of higher insurance charges.
* **Age Factor:** Charges strictly increase with age, adding an average of $267 per year of life.
* **The Obesity-Smoking Penalty:** High BMI significantly increases costs, but primarily for smokers. The econometric model reveals a massive ~$20,000 threshold "penalty" for crossing into clinical obesity as a smoker.
* **Model Performance:** The final reduced linear model explains over **86% of the variance** in insurance charges using just four predictors.
* **Data Limitations:** The analysis deduces that unobserved variables (likely chronic diseases or family's medical history) play a major role in pricing, creating distinct clusters in the middle-cost band that the available dataset cannot fully explain.

<img width="880" height="423" alt="image" src="https://github.com/user-attachments/assets/15bca84d-9595-4130-b818-b0d959435333" />


# How to View

You can view the full report directly via GitHub Pages:
**[Click here to view the Analysis & Model](https://margor6.github.io/insurance-prices-eda-modeling/medical_insurance_eda.html)**

## Author: Marcin Górski
