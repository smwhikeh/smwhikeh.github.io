---
title: HMS 520 Introduction to Programming, Version Control, And Data Wrangling For Health Metrics Sciences 
summary: IHME (GBD 2021) Tuberculosis Estimates 1990-2021
date: 2024-12-06
type: docs
math: false
tags:
  - Data Science
image:
  caption: 'HMS520'

---
## Overview

This class covered the basics of programming including **communicating with machines**, writing **clean code** and **collaborative programming**. More specifically in this class I learned *git* and *R* and built a **codebase** to deal with a series of tasks focused on **data manipulation**. In this course I used *R* to **manipulate data** and create **simple models** and **analysis** as well as understanding, recognizing and writing clean code for readability and extendability. Finally, I also tested, debugged and documented R functions that I wrote. 

---

## Final Project for HMS520 Data Analysis for (GBD 2021) Tuberculosis Estimates 1990-2021

Collaborator: Ye Htet Naing MD, MPH


**Background**

This project explored the **global mortality trends** and **risk factor** contributions to **tuberculosis (TB)** between 2015 and 2019 using data from the **Institute for Health Metrics and Evaluation (IHME) Global Burden of Disease 2021 (GBD 2021)** study. Access to the data can be found [here](https://ghdx.healthdata.org/record/ihme-data/gbd-2021-tuberculosis-incidence-mortality-1990-2021). In support of the **World Health Organization's** End TB Strategy, which targeted a **35% reduction** in TB mortality and a **20% reduction** in TB incidence by 2020, we examined whether these goals were achieved across different regions and age groups, and how much modifiable risk factors like **smoking**, **alcohol use**, and **diabetes** contributed to **TB mortality**. 

**Key Objectives** 

Using GBD data we aimed to answer the following key questions: 

1. How have **mortality rates** changed from 2015 to 2020 across different age groups and regions?

2. What is the **relative contribution** of different **risk factors** (e.g., smoking, alcohol use, and diabetes) to TB mortality in 2015 and 2020?

3. Do regions or age groups with **higher reductions** in TB mortality also show lower contributions of risk factors?

**Data and Methods** 

Our analysis included: 

- **Preprocessing and Cleaning**: Filtering relevant columns, checking for missing data and creating derived variables 
- **Trend Analysis**: Calculated percent change in mortality by region and age groups (2015-2020)
- **Risk Factor Analysis**: Assessed proportion of TB mortality attributable to each risk factor 
- **Regression Analysis**: Explored associations between reductions in mortality and changes in attributable risks

**Key Visualizations**

**Figure 1: Mean Mortality Change from 2015 - 2020 (All Ages)**

![fig1](fig1.png)

**Figure 2. Attributable Mortality by Age Group**

![fig2](fig2.png)

**Figure 3. Attributable Mortality by Region**

![fig3](fig3.png)

**Figure 4. Linear Regression: Mortality Reduction vs Risk Factor Contribution**

![fig4](fig4.png)

**Findings and Interpretation**

Our analysis examined TB mortality trends from 2015 to 2020 across regions, age groups and risk factors.

**Regional and Age-Specific Mortality Trends**

- TB mortality changes **varied widely by region**, Eastern Europe, Central Europe and Central Asia had the **greatest reductions**. 

- In contrast, High-income North America, Oceania and Central Latin America experiences **increases** which point to potential **systemic** or **healthcare challenges**.

- Across regions, adults (ages 50-69 and 70+) 
consistently showed the **highest increases** in mortality which emphasize the need for **targeted interventions for aging population**s.

**Risk Factor Contributions**

- Risk patterns shifted with age: ages **15-49 Diabetes** was the leading contributor and ages **50-69 and 70+ alcohol use** became dominant, with smoking also significant among older adults. 

- Regionally, Sub-Saharan Africa and South Asia had the **highest risk-attributable mortality** which likely reflect **disparities** in healthcare access and chronic disease management. 

- These findings highlight the need for **age-specific** and **region-specific** prevention strategies.

**Link Between Mortality Reduction and Risk Factors**

- A linear regression analysis showed **no significant relationship** between mortality reduction and average risk factor contribution. 

- This suggests that mortality improvements may be driven by more **broader healthcare advancements** than by reductions in individual risk factors.

- Future efforts should consider **additional determinants** of TB mortality to guide policy and intervention priorities. 


**Conclusion**

Our analysis shows the importance of **age and region specific TB strategies** and highlights the ongoing role of **modifiable risk factors in driving TB mortality**. These insights can inform **tailored public health interventions** and help guide progress towards **TB elimination** goals worldwide. 

[Download Project Report (PDF)](hms_520_tb_final.pdf)

[GitHub Code Repository](https://github.com/smwhikeh/HMS_520_Final_Project_TB)