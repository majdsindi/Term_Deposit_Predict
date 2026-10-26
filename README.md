# Term Deposit Subscription Prediction

## Overview
This project focuses on analyzing bank customer data and building predictive models to identify customers likely to subscribe to a term deposit. Using exploratory data analysis (EDA) and machine learning techniques, the project aims to help financial institutions optimize their direct marketing campaigns, improve conversion rates, and reduce operational costs associated with targeted outreach.

## Dataset
The project utilizes a bank marketing dataset containing **40,000 observations** and **14 features** detailing customer demographics, financial background, and campaign contact information.

### Key Features:
- **Demographics & Financial Profile:** `age`, `job`, `marital`, `education`, `default`, `balance`, `housing`, `loan`
- **Campaign & Contact Information:** `contact`, `day`, `month`, `duration`, `campaign`
- **Target Variable (`y`):** Subscription status (`yes` / `no`)

### Dataset Characteristics:
- **No Missing Values:** The dataset contains no explicit null values (`NaN`), though some categorical variables (`job`, `education`, `contact`) include `'unknown'` entries.
- **Class Imbalance:** Highly imbalanced target variable (`y`), with approximately **93% "no"** (did not subscribe) and **7% "yes"** (subscribed).

## Project Workflow
1. **Setup & Environment:** Environment configuration and dependency management using Python data science libraries.
2. **Data Ingestion:** Loading and inspecting dataset properties, data types, and structural statistics.
3. **Exploratory Data Analysis (EDA):**
   - Analysis of target variable distribution and class imbalance.
   - Categorical feature inspection across customer segments (job types, marital status, education level).
   - Analysis of direct marketing contact efforts and interactions.

## Tech Stack & Dependencies
- **Programming Language:** Python
- **Data Manipulation:** `pandas`, `numpy`
- **Data Visualization:** `matplotlib`, `seaborn`
- **Machine Learning & Modeling:** `scikit-learn`, `xgboost`, `tensorflow`, `lazypredict`

