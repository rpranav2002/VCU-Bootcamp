# Assignment 1: Data Audit and Exploratory Data Analysis (EDA)

## Overview

This repository contains the deliverables for **Assignment 1: Data Audit and Exploratory Data Analysis (EDA)** for **MBAV 443M – Statistical Modeling and AI-Driven Analytics**.

The analysis was conducted using the **Online Retail Dataset** and focuses on assessing data quality, exploring dataset characteristics, generating visualizations, and identifying key business insights.

---

## Repository Structure

```text
.
├── Online Retail.xlsx
├── notebook.ipynb
├── report.pdf
├── Online_Retail_Assignment_Report.docx
└── README.md
```

---

## Dataset

**Dataset Name:** Online Retail

The dataset contains transactional records from an online retail business, including:

* Invoice information
* Product details
* Quantity purchased
* Unit price
* Customer identifiers
* Country information

---

## Objectives

The primary objectives of this analysis are:

1. Understand the structure of the dataset.
2. Assess data quality.
3. Identify missing values and duplicate records.
4. Generate descriptive statistics.
5. Detect outliers and unusual observations.
6. Explore relationships between variables.
7. Create informative visualizations.
8. Derive meaningful business insights.

---

## Tools and Libraries

The analysis was performed using Python and the following libraries:

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Analysis Performed

The notebook includes:

### 1. Dataset Overview

* Dataset dimensions
* Variable inspection
* Data type verification

### 2. Data Quality Assessment

* Missing value analysis
* Duplicate record identification

### 3. Descriptive Statistics

* Summary statistics for numerical variables
* Distribution analysis

### 4. Outlier Detection

* Boxplot analysis
* Identification of extreme values

### 5. Relationship Exploration

* Quantity vs. Unit Price analysis
* Transaction pattern exploration

### 6. Country Analysis

* Transaction distribution by country
* Identification of major markets

---

## Key Findings

* The dataset contains missing values, primarily in the CustomerID field.
* Duplicate records were identified and should be reviewed before modeling.
* Quantity and UnitPrice exhibit significant skewness and outliers.
* Negative quantities likely represent returns or cancelled transactions.
* The United Kingdom accounts for the majority of transactions.

---

## Deliverables

### Jupyter Notebook

`notebook.ipynb`

Contains all code, visualizations, and analysis steps.

### Report

`report.pdf` / `Online_Retail_Assignment_Report.docx`

Provides a concise summary of the exploratory analysis, findings, and recommendations.

---

## AI Usage Disclosure

Generative AI tools were used for coding assistance and language refinement. All analysis, validation, interpretation, and conclusions remain the responsibility of the author.

---

## Course Information

**Course Code:** MBAV 443M
**Course Title:** Statistical Modeling and AI-Driven Analytics

**Assignment:** Assignment 1 – Data Audit and Exploratory Data Analysis (EDA)
