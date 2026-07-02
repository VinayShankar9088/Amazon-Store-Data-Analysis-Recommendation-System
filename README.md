# Amazon Store Data Analysis

## Overview

This practice focuses on analyzing customer review data from an Amazon-like store dataset using Python. It includes data cleaning, basic data analysis, and simple product suggestions based on customer ratings.

## Features

* Load customer data from JSON files
* Clean and structure raw data
* Remove duplicate records
* Handle missing values
* Calculate average customer ratings
* Identify poor rating percentage
* Generate simple product suggestions

## Technologies Used

* Python
* JSON
* Jupyter Notebook

## Practice Workflow

1. Load raw customer data from a JSON file
2. Clean and preprocess the dataset
3. Analyze customer ratings
4. Generate meaningful insights
5. Suggest products based on customer ratings

## Sample Insights

* Average Customer Rating: 3.6
* Poor Ratings (< 3): 25%

## Product Suggestion Logic

* Rating >= 4 → Apple
* Rating < 4 → Samsung

## Project Structure

```text
Amazon-Store-Data-Analysis/
│
├── data/
│   └── store_data.json
│
├── notebooks/
│   └── amazon_store_analysis.ipynb
│
├── README.md
│
└── requirements.txt
```

## Purpose

This repository was created to practice data cleaning, exploratory data analysis (EDA), and basic decision-making using Python and JSON data.
