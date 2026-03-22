# Workplace Absenteeism Analytics

Explored workplace absenteeism patterns using the UCI Absenteeism dataset in R. Analyzed absence hours by month, age, smoking/drinking status, and physical attributes through scatter plots, histograms, and boxplots. Found absences peak in March/July and skew toward shorter durations.

## Overview

Exploratory data analysis of the [UCI Absenteeism at Work dataset](https://archive.ics.uci.edu/ml/datasets/Absenteeism+at+work), examining patterns in employee absence across demographic, behavioral, and temporal variables.

## Tools & Technologies

- **Language:** R
- **Libraries:** Base R graphics
- **Report:** R Markdown

## Dataset

- **Source:** UCI Machine Learning Repository
- **Format:** CSV (semicolon-delimited)
- **Key Variables:** Absenteeism time (hours), age, month of absence, social smoker/drinker status, height, weight

## Key Findings

- **Absence Duration:** Highly right-skewed — most absences are short, with few extended absences
- **Age:** Bimodal distribution with peaks before age 40 and around age 45–50
- **Monthly Trends:** Highest absence hours in March and July; lowest in January and August/September
- **Smoking:** Social smokers showed slightly lower absenteeism than non-smokers
- **Drinking:** Minimal difference in absenteeism between drinkers and non-drinkers

## Project Structure

```
├── Absenteeism_at_work.csv     # Dataset
├── nmahaja8_Lab1.rmd           # R Markdown source
├── nmahaja8_Lab1.pdf           # Rendered report
└── README.md
```

## How to Run

1. Clone the repository
2. Open `nmahaja8_Lab1.rmd` in RStudio
3. Ensure the CSV is in the same directory
4. Knit the R Markdown file to reproduce the report
