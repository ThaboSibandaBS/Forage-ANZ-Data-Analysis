# Forage: Data@ANZ Virtual Experience Program

This repository contains my solution to the [*Data@ANZ Virtual Experience Program*](https://www.theforage.com/simulations/anz/data-analytics-and-visualisation-qcn9?ref=DsEXFixxovqkRxR2u&reloaded=true) on Forage.

## Introduction

This project is part of the ANZ Virtual Experience Programme, focusing on extracting meaningful insights from the synthesised customer transaction dataset by ANZ. The work spans two core areas: understanding customer spending behaviour through exploratory analysis, and building predictive models to estimate customer income. Both tasks combine Python-based data analysis with visualisation and machine learning techniques to simulate the kind of work ANZ's data team performs on real-world banking data.

---

## Task 1: Exploratory Data Analysis

The goal of this task was to uncover patterns and trends hidden within the transaction data through careful examination and visualisation.

The analysis began with a data quality review - checking for missing values, inconsistencies, or records that would need to be cleaned before drawing any conclusions. Once the data was confirmed reliable, a broad set of descriptive statistics were computed to establish a baseline understanding: typical transaction amounts, how frequently customers transact, and how activity varies from month to month.

The dataset was then broken down by transaction date and time to reveal behavioural patterns across the course of a day and across different days of the week. Visualisations of transaction volume and spending levels were produced to highlight when customers are most active. Outliers were identified and their potential distorting effect on the overall analysis was carefully considered.

As an extension, the geographic location data embedded in the dataset was examined to see whether spending patterns differ by region or location type.

---

## Task 2: Predictive Analytics

This task shifted from description to prediction, using the transaction data to build models capable of estimating each customer's annual salary.

Annual salary was first derived per customer from the available transaction records. A correlation analysis was then conducted between salary and a range of customer attributes - some drawn directly from the data and others engineered from transaction behaviour. Relationships of interest were visualised using scatter plots to inform feature selection.

A linear regression model was trained on the selected features to predict annual salary. The model's accuracy was evaluated and its suitability for segmenting ANZ customers into income brackets was assessed critically - not just whether it works technically, but whether it is reliable enough to drive real business decisions.

As an extension, a decision tree model was also developed and benchmarked against the regression approach, with a discussion of which evaluation method most fairly reflects each model's true predictive performance.

---

## Tools and Libraries

- Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)
- Jupyter Notebook

---

## Repository Structure

```
├── anz_internship_raw_data.csv
├── ANZ_Data@ANZ_Program_EDA.ipynb
├── ANZ_Data@ANZ_Program_EDA - Thabo Sibanda.pdf
└── README.md
```

---

## Author

**Thabo Sibanda**
MSc Chemical Engineering | R&D Engineer | Data Analytics Enthusiast
[LinkedIn](https://www.linkedin.com/in/thabosibanda) · [GitHub](https://github.com/thabosibanda)
