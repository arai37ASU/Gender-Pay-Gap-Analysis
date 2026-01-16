# Gender Pay Gap Analysis 📊

## Project Overview
This project analyzes gender-based compensation disparities using the **Glassdoor Gender Pay Gap dataset**. The goal is to uncover how pay differences vary across **education level, job title, department, seniority, performance evaluations, and bonuses**, and to highlight areas where inequities persist.

The analysis combines **data cleaning, exploratory data analysis (EDA), and data visualization** to generate actionable insights relevant to organizations, policymakers, and analysts interested in workplace equity.

---

## Key Questions Explored
- How does the gender pay gap vary across **industries and job titles**?
- Does **higher education** reduce or widen pay disparities?
- How do **seniority and performance evaluations** impact compensation differences?
- Are **bonuses distributed equitably** across genders?

---

## Dataset
- **Source:** Glassdoor Gender Pay Gap Dataset (Kaggle)
- **Observations:** ~1,000 employee records
- **Key Features:**
  - Gender
  - Age
  - Education level
  - Job title
  - Department
  - Seniority
  - Performance evaluation score
  - Base pay
  - Bonus

> Note: The dataset represents self-reported Glassdoor data and may not fully capture all industries or regions.

---

## Tools & Technologies
- **R**
- **Libraries Used:**
  - `dplyr`
  - `ggplot2`
  - `tidyr`
  - `readr`
  - `plotly`

---

## Data Cleaning & Preparation
- Removed incomplete records
- Handled outliers using Z-score filtering on base pay
- Converted categorical variables into factors
- Created derived metrics such as **total compensation (base pay + bonus)**

---

## Visual Analysis Highlights
The project includes multiple visualizations, such as:

- **Education vs. Base Pay by Gender**  
  Shows widening pay gaps at higher education levels.

- **Base Pay by Job Title and Gender**  
  Highlights roles with persistent disparities and a few where women earn more.

- **Department-wise Pay Distribution (Stacked Area Chart)**  
  Illustrates cumulative compensation differences across departments.

- **Bonus Distribution by Gender (Box Plot)**  
  Reveals consistently higher bonuses for male employees.

- **Base Pay vs. Seniority (Scatter Plot)**  
  Demonstrates slower pay progression for women at similar experience levels.

- **Performance vs. Total Compensation (Interactive Plot)**  
  Shows compensation gaps even at comparable performance scores.

---

## Key Findings
- Higher education correlates with higher pay for both genders, **but the pay gap widens at advanced levels (especially PhD)**.
- Male employees generally earn higher base pay and bonuses across most job titles.
- Departments such as **Engineering and Management** show significant cumulative pay disparities.
- Even with similar seniority and performance ratings, **women often receive lower total compensation**.

---

## Limitations
- Self-reported Glassdoor data may introduce bias
- Analysis focuses on correlation, not causation
- No time-series data to analyze trends over multiple years
- Factors like negotiation behavior, career breaks, or geographic cost-of-living are not included

---

## Recommendations
- Conduct regular pay equity audits
- Standardize performance evaluation criteria
- Increase pay transparency
- Invest in targeted career development and mentorship programs for women
- Strengthen enforcement of equal pay policies

---

## How to Run the Project
1. Clone this repository  
   ```bash
   git clone https://github.com/your-username/gender-pay-gap-analysis.git
