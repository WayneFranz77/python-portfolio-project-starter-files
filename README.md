# U.S. Medical Insurance Costs Analysis

A Python data analysis project investigating demographic and risk factors influencing healthcare charges using real-world medical insurance data.

## Project Overview
This project explores the `insurance.csv` dataset to identify primary drivers of medical costs. Key areas of focus include:
- Exploratory data analysis using base Python classes as well as `pandas`, `numpy`, and `seaborn`.
- Quantifying the cost differential between smokers and non-smokers.
- Analyzing non-linear compounding effects between BMI and smoking status.
- Evaluating dataset sampling bias and limitations for real-world risk modeling.

## Key Findings
- **Smoker Status:** Smoking is the strongest single predictor of medical charges, resulting in significantly higher average costs ($32k+ vs. ~$8.4k).
- **BMI & Smoking Interaction:** Individuals with a high BMI ($\ge 30$) who smoke experience exponential cost increases compared to high-BMI non-smokers.
- **Age:** Demonstrates a steady, linear positive correlation with insurance charges.

## Files
- `us-medical-insurance-costs.ipynb`: Complete analysis notebook with data structures, visualizations, and insights.
- `insurance.csv`: Medical insurance dataset.