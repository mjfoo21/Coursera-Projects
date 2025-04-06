# Retail Data Analysis

## 📌 Project Overview
This project aims to perform exploratory data analysis on transactional data from an online retail store.

## 🔍 Project Workflow
### 1. Data Preprocessing
- Examined the datasets for missing data, incorrect information, duplicates.
- Performed necessary rectifications to clean the data

### 2. Data Exploration
- Separated sales and cancellation datasets.
- Identified trends and patterns in data and produced statistical reports of customer profiles, products, purchase patterns.
- Visualized data in terms of patterns and graphs.

### 3. Building Recommendation Models
- Tested various recommendation models, including popularity model, neighbourhood-based recommendation and collaborative filtering.
- Identified neighbourhood-based model as the best performer, achieving a **recall@5 score of 0.49** and a **recall@10 score of 0.64**. This means that in 49% of the cases, the product a user eventually chose was among the model’s top 5 recommendations, and in 64% of the cases, it was within the top 10.

## 📂 Repository Structure
- `online_retail.ipynb` - Jupyter notebook containing the full analysis, model building, and evaluation process.
- `Online Retail.xlsx` - Retail dataset.
- `README.md` - Project documentation.