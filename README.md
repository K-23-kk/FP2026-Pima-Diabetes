# Pima Indians Diabetes Dataset Analysis

[![View Analysis](https://img.shields.io/badge/View-Analysis-blue)](https://k-23-kk.github.io/FP2026-Pima-Diabetes/)

## 📊 Overview

This analysis explores the Pima Indians Diabetes Dataset containing medical measurements for 768 female patients. The data was collected by the National Institute of Diabetes and Digestive and Kidney Diseases and includes diagnostic measurements to investigate diabetes risk factors. The Pima Indian population has historically shown high diabetes prevalence, making this dataset valuable for understanding disease predictors.
Data was originally collected in the 1990s from Pima Indian women aged 21+ living near Phoenix, Arizona

## 🎯 Research Questions

1. How do glucose levels differ between diabetes groups?
2. Is BMI associated with diabetes?
3. Does age affect diabetes prevalence?
4. What is the relationship between pregnancies and diabetes?
5. Do blood pressure levels differ between groups?
6. Is insulin level associated with diabetes outcome?
7. Which variables show the strongest differences?
8. Which factor combinations appear most risky?

## 🔍 Key Findings

- **Glucose** is the strongest predictor (effect size: 1.07), validating its use as the primary diagnostic criterion
- **BMI** shows strong association with diabetes (4.8 point difference between groups)
- **Age-related risk** increases dramatically, with prevalence rising from 21.6% (21-30 years) to 56.6% (41-50 years)
- **High-risk combinations**: High glucose + elevated BMI + advanced age creates the highest risk profile
- Overall diabetes prevalence in this population: **34.9%**

## 🛠️ Methodology

- **Statistical Analysis**: Cohen's d effect sizes for standardized comparison across variables
- **Visualization**: Violin plots with box plots, bar charts, and 2D risk profiles
- **Tools**: R, ggplot2, dplyr, Quarto
- **Approach**: Modular, reproducible code with reusable functions

## 📁 Repository Structure
```
FP2026-Pima-Diabetes/
├── diabetes_analysis.qmd       # Main analysis document
├── Pima_diabetes.csv            # Dataset
├── README.md                    # This file
└── docs/                        # Rendered HTML output
```

## 🚀 Reproducibility

To reproduce the analysis:

1. Clone this repository
2. Ensure R and required packages are installed (`dplyr`, `ggplot2`, `tidyr`, `gridExtra`)
3. Open `diabetes_analysis.qmd` in RStudio
4. Click "Render" to generate the HTML report

## 👤 Author

**Krishna Kousalya Kesavan**  
Fundamentals of Programming - Coding Project  
*February 22, 2026*

## 📝 License

This project is part of an academic assignment analyzing publicly available health data.

---

**[📊 View Full Analysis](https://k-23-kk.github.io/FP2026-Pima-Diabetes/)**
