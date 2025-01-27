# Zeotap Data Science Assignment
This repository includes tasks on exploratory data analysis (EDA), lookalike modeling, and customer segmentation.

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Tasks](#tasks)
  - [Task 1: Exploratory Data Analysis (EDA) and Business Insights](#task-1-exploratory-data-analysis-eda-and-business-insights)
  - [Task 2: Lookalike Model](#task-2-lookalike-model)
  - [Task 3: Customer Segmentation / Clustering](#task-3-customer-segmentation--clustering)
- [Files in the Repository](#files-in-the-repository)
- [Setup and Execution](#setup-and-execution)
- [Results](#results)
- [References](#references)

## Overview
This project analyzes eCommerce transaction data to derive actionable insights, build a lookalike model for recommending similar customers, and segment customers using clustering techniques. It demonstrates data analysis, machine learning, and visualization skills to improve business strategy.

## Dataset
The dataset consists of three files:
1. **Customers.csv**: Contains customer details.
2. **Products.csv**: Contains product details.
3. **Transactions.csv**: Contains transaction details.

Download the dataset from the following links:
- [Customers.csv](https://drive.google.com/file/d/1bu_--mo79VdUG9oin4ybfFGRUSXAe-WE/view?usp=sharing)
- [Products.csv](https://drive.google.com/file/d/1IKuDizVapw-hyktwfpoAoaGtHtTNHfd0/view?usp=sharing)
- [Transactions.csv](https://drive.google.com/file/d/1saEqdbBB-vuk2hxoAf4TzDEsykdKlzbF/view?usp=sharing)

## Tasks

### Task 1: Exploratory Data Analysis (EDA) and Business Insights
- Conducted EDA to understand the dataset.
- Derived 5 actionable business insights from the analysis.

### Task 2: Lookalike Model
- Built a lookalike model to recommend 3 similar customers based on profile and transaction history.
- Generated a "Lookalike.csv" file for the first 20 customers with similarity scores.

### Task 3: Customer Segmentation / Clustering
- Performed customer segmentation using clustering techniques.
- Calculated clustering metrics, including the Davies-Bouldin Index.
- Visualized the clusters and provided insights based on the segmentation.

## Files in the Repository
- **Shrinath_Asati_EDA.pdf**: Report on EDA and business insights.
- **Shrinath_Asati_EDA.ipynb**: Jupyter Notebook for EDA.
- **Shrinath_Asati_Lookalike.csv**: Output file containing similarity scores for the first 20 customers.
- **Shrinath_Asati_Lookalike.ipynb**: Jupyter Notebook for the lookalike model.
- **Shrinath_Asati_Clustering.pdf**: Report on customer segmentation and clustering.
- **Shrinath_Asati_Clustering.ipynb**: Jupyter Notebook for customer segmentation.

## Setup and Execution
### Prerequisites
- Python 3.8 or higher
- Libraries: pandas, numpy, matplotlib, seaborn, sklearn

### Steps to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/shrinathasati/Zeotap_data_science_assignment.git
   
   ```
2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```
3. Place the dataset files (`Customers.csv`, `Products.csv`, and `Transactions.csv`).
4. Run the Jupyter Notebooks:
   ```bash
   jupyter notebook
   ```
5. Open and execute the following notebooks:
   - **Shrinath_Asati_EDA.ipynb** for Task 1 (EDA)
   - **Shrinath_Asati_Lookalike.ipynb** for Task 2 (Lookalike Model)
   - **Shrinath_Asati_Clustering.ipynb** for Task 3 (Clustering)

## Results
- **EDA**: Provided detailed insights into customer behavior, product performance, and transaction trends.
- **Lookalike Model**: Recommended similar customers with computed similarity scores.
- **Customer Segmentation**: Segmented customers into distinct clusters with metrics and visualizations.

## References
- Dataset: Provided as part of the assignment.
- Python Libraries: pandas, numpy, matplotlib, seaborn, sklearn

---
