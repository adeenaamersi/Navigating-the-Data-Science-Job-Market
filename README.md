# Exploratory Data Analysis - Cleaned Data Science Job Market & Salaries 2024

## Overview
The data science job market in 2024 is thriving, fueled by advancements in AI, machine learning, and data analytics. This project leverages the Cleaned Data Science Job Market & Salaries 2024 dataset to analyze trends in salaries, skills, roles, and geographical demand. By performing exploratory data analysis (EDA), the goal is to uncover actionable insights that benefit job seekers, employers, and researchers, providing a clearer understanding of the current job market landscape.

## Case Study: Navigating the Data Science Job Market
The data science field is rich with opportunities, offering diverse roles and salary ranges. However, both job seekers and employers face unique challenges:

Job seekers must navigate regional salary differences, identify in-demand skills, and evaluate how experience impacts compensation.
Employers need to benchmark salaries and assess industry standards to attract top talent.
This case study addresses these challenges by analyzing critical questions:

1. What are the most common job positions in data science?

2. What are the top-paying roles, companies, and locations?

3. What is the relationship between company rating and salary?

## Dataset
The dataset used for this analysis is the Cleaned Data Science Job Market & Salaries 2024 dataset, sourced from Kaggle. It contains detailed information about job postings in the data science field, including roles, salaries, company ratings, and more.

### Dataset Columns

| Column Name      | Description                                                                 |
|-------------------|-----------------------------------------------------------------------------|
| `Job Title`       | The title of the job position being advertised (e.g., Data Scientist, Machine Learning Engineer, Data Analyst). |
| `Company Name`    | The name of the company offering the job position.                        |
| `Location`        | The geographical location where the job is based.                         |
| `Job Link`        | A URL to the job posting for more details.                                |
| `Company Rating`  | A rating out of 5 for the company, typically based on employee reviews.   |
| `Min Salary`      | The minimum salary offered for the position, extracted from the original salary range. |
| `Max Salary`      | The maximum salary offered for the position, extracted from the original salary range. |
| `Posting Date`    | The date when the job was posted, converted from a relative time format (e.g., 30d+) to an actual date. |

### Dataset Overview

**Number of Rows**: 485

**Number of Columns**: 8

**Data Source**: Kaggle - Cleaned Data Science Job Market & Salaries 2024

The dataset is well-structured and pre-cleaned, making it ideal for EDA to uncover trends and insights.

## Tasks
The analysis process is guided by the following tasks:

1. Data Loading and Inspection
    - Load the dataset into a data analysis environment.
    - Inspect the dataset structure, data types, and overall quality.
    - Identify and address missing values or inconsistencies.

2. Data Cleaning
    - Handle missing values and duplicates.
    - Remove unnecessary columns.
    - Create new columns to enhance data analysis.
    
3. Analysis of Most Popular Jobs
    - Identify the most common job positions in the data science field.

4. Salary Analysis
    - Explore salary trends across job roles, companies, and locations.
    - Examine the relationship between company ratings and salaries.
    
## Insights and Goals
Through this analysis, the project aims to provide valuable insights into the data science job market, helping individuals align their skills and expectations with market demand. Employers can leverage these insights to benchmark salaries and identify competitive opportunities. Ultimately, this project seeks to make navigating the data science job market more transparent and data-driven.

For any questions or contributions, feel free to reach out!
