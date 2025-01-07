
# Contingency Tables: Aspirin - The Miracle Drug? 

## Project Overview
This project examines the effects of aspirin on heart attack prevention using contingency tables and statistical methods. The study evaluates the relationship between aspirin use and heart attack occurrence by analyzing categorical data through measures like risk ratios, odds ratios, and chi-squared tests.

## Dataset
The dataset, **Aspirin.csv**, contains 20,021 observations from a double-blind experimental study conducted in 1993. Key features include:
- **Group**: Participants taking either aspirin or a placebo.
- **HeartAttack**: Indicates whether a participant had a heart attack (`Yes` or `No`).
- **Smoking**: Participant smoking status (`Smoker` or `Non-Smoker`).
- **Age**: Participant's age categorized into six groups (`61`, `62`, ..., `65`).

## Objectives
1. Analyze the distribution of heart attack occurrence across groups.
2. Evaluate the strength of the association between aspirin use and heart attack prevention using:
   - **Risk Ratio (RR)**
   - **Odds Ratio (OR)**
3. Test the independence between aspirin use and heart attack occurrence using the chi-squared test.

## Statistical Methods
- **Two-way contingency tables**: To represent the joint distribution of categorical variables.
- **Risk Ratio (RR)**: Measures the relative risk of heart attacks in aspirin vs. placebo groups.
- **Odds Ratio (OR)**: Compares the odds of heart attacks between aspirin and placebo groups.
- **Chi-squared test**: Tests the independence of categorical variables.

## Key Findings
1. **Risk and Odds**: 
   - Aspirin reduces the risk of heart attacks by nearly **58%**.
   - Odds of heart attacks for aspirin users are approximately **40%** of the odds for placebo users.
2. **Chi-squared Test**:
   - A strong dependency exists between aspirin intake and heart attack prevention, with a p-value < 2.2e-16.
3. **Additional Insights**:
   - Smokers have a significantly higher rate of heart attacks compared to non-smokers.
   - Age does not significantly influence heart attack rates.

## Tools and Libraries
The analysis was conducted using **R** with the following libraries:
- `epitools`: Handling contingency tables
- `dplyr`: Data manipulation
- `ggplot2`: Data visualization
