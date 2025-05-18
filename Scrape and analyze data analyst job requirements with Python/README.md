# Scrape and Analyze Job Requirements with Python

## 📌 Project Overview
This project aims to build a streamlined system for extracting and analyzing job postings to support recruitment agencies in identifying relevant roles for candidates efficiently.

## 🔍 Project Workflow
### 1. Web Scraping
- Collected job posting data from a publicly available static website.
- Extracted key job information such as title, company, and location, and exported into a DataFrame.

### 2. Data Preprocessing
- Integrated an external dataset from Kaggle [LinkedIn Job Postings](https://www.kaggle.com/datasets/arshkon/linkedin-job-postings/data) to simulate real-world job data.
- Cleaned the data by handling missing values and inconsistencies.
- Merged multiple tables to consolidate job, company, and role details.

### 3. Data Analysis
- Explored job distribution by industry, company size, experience level, and employment type.
- Identified high-demand industries and skill sets.
- Clustered job titles using LLM-based embeddings and visualized clusters using TF-IDF keywords.
- Analyzed trends in specific roles such as data analysts and nurses.

### 4. Candidate Matching
- Developed a basic recommendation system to suggest job roles based on a candidate’s profile.
- Matched roles using key criteria such as required skills, experience, and remote work options.
- Demonstrated the ability to automate role suggestions with reasonable accuracy.

## 📂 Repository Structure
- `scrape_job.ipynb` - Jupyter notebook containing the scraping process, analysis, and recommendation system.
- `kmeans_normed_pca10_results.csv` - Clustering results.
- `README.md` - Project documentation.
- *Note: Due to GitHub storage constraints, the Kaggle dataset is not included in this repository. Please refer to the original data source to access the dataset.*