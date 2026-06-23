# Amazon Store Data Analysis & Recommendation System

## Overview

This project analyzes customer review data from an Amazon-like store dataset. The system performs data cleaning, generates business insights, and provides basic product recommendations based on customer ratings.

## Features

* Load customer data from JSON files
* Clean and structure raw data
* Remove duplicate records
* Handle missing values
* Calculate average customer ratings
* Identify poor rating percentage
* Generate simple product recommendations

## Technologies Used

* Python
* JSON
* Jupyter Notebook

## Project Workflow

1. Load raw customer data from JSON file
2. Clean and preprocess the dataset
3. Analyze customer ratings
4. Generate meaningful insights
5. Recommend products based on customer ratings

## Sample Insights

* Average Customer Rating: 3.9
* Poor Ratings (< 3): 20%

## Recommendation Logic

* Rating >= 4 → Apple
* Rating < 4 → Samsung

## Project Structure

```
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

## Future Improvements

* Sentiment Analysis on customer feedback
* Machine Learning recommendation system
* Interactive dashboard using Streamlit
* Data visualization with Matplotlib and Seaborn
