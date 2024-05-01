# Homework 3: Survival Analysis

## Overview
This project focuses on conducting survival analysis on a telecommunications dataset to understand the factors affecting churn risk and calculate Customer Lifetime Value (CLV) per customer based on the final model. The goal is to identify valuable customer segments and propose retention strategies.

## Dataset
The dataset contains the following features:
- ID: Subscriber ID
- region: Region code
- tenure: Lifetime
- age: Subscriber’s age
- marital: Subscriber’s marital status
- address: Number of years living in the same address
- income: Subscriber’s annual income (K)
- ed: Education level
- retire: Retired (Yes/No)
- gender
- voice
- internet
- forward: Call forwarding
- custcat: Customer category
- churn: Churn status (Yes/No)

## Tasks
1. **Parametric Models:**
    - Build Accelerated Failure Time (AFT) models with all available distributions.
    - Compare the models and visualize all the curves in one plot.
    - Determine the preferred model considering factors beyond comparison metrics.
    - Retain significant features and finalize the model.

2. **Customer Lifetime Value (CLV):**
    - Calculate CLV per customer based on the final model.
    - Explore CLV within different segments to identify valuable customer groups.

3. **Report:**
    - Interpret the coefficients of the final model.
    - Define the criteria for being valuable and identify the most valuable segments.
    - Estimate the annual retention budget based on CLV, survival probabilities, and the number of at-risk subscribers within a year.
    - Propose additional retention strategies beyond the model findings.

## File Structure
- `data/telco.csv`: CSV file of our data
- `codes.ipynb`: Jupyter Notebook containing the code for data analysis, model building, and visualization.
- `README.md`: This file providing an overview of the project, tasks, and file structure.
- `dataset.csv`: The telecommunications dataset used for analysis.

## Instructions
1. Open the `codes.ipynb` notebook in Jupyter Notebook or JupyterLab.
2. Follow the code cells to execute the analysis steps outlined in the tasks.
3. Refer to the comments and markdown cells for explanations and interpretations.

## Dependencies
- Python 3.x
- Libraries: pandas, numpy, matplotlib, seaborn, lifelines

## Author
Yeva Manukyan

## Acknowledgments
This project is part of a homework assignment for a course. Data source and task details provided by the instructor.
