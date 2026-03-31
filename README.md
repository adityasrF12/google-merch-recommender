# Google Merchandise Recommendation System
**Course Project: CIS-5570 Introduction to Big Data**

## Overview
This project implements a recommendation engine using the **Alternating Least Squares (ALS)** algorithm in **PySpark**. It analyzes implicit feedback from the Google Merchandise Store dataset to provide personalized product suggestions.

## Key Features
* **Scalable Data Processing:** Built using PySpark for large-scale data handling.
* **Implicit Feedback Modeling:** Utilizes interaction weights to account for different user behaviors (clicks, adds to cart, purchases).
* **Evaluation:** Achieved a Model RMSE of **0.120** vs a Baseline RMSE of **0.341**.

## Technical Stack
* **Language:** Python
* **Framework:** PySpark (Spark MLlib)
* **Libraries:** Pandas, Matplotlib, Seaborn

## Data Source
The dataset used is the [Google Merchandise Sales Data](https://www.kaggle.com/datasets/mexwell/google-merchandise-sales-data) from Kaggle.
