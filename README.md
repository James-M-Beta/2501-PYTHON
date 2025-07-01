# 2501-PYTHON

This repository is for demonstration purposes only
![Github Desktop](imgs/img1.png)
This repository contains:

- A sample dataset with 1 year of stock data (sampled every 3 days)
- A Python notebook/script that:
  - Loads the data from a local file or GitHub
  - Cleans and explores the dataset
  - Visualizes trends and returns
  - Conducts a basic statistical test (t-test)
  - Summarizes findings

---

## Data Description

The dataset includes the following columns:

| Column       | Description                               |
|--------------|-------------------------------------------|
| Date         | Trading date (every 3rd day)              |
| Open         | Opening price of the stock                |
| High         | Highest price on that trading day         |
| Low          | Lowest price on that trading day          |
| Close        | Closing price of the stock                |
| Volume       | Total trading volume                      |

---

## Key Steps in the Analysis

1. **Importing the Data**  
   - Read the CSV locally or from a GitHub raw link.

2. **Data Cleaning & Setup**  
   - Convert date column, sort chronologically, handle missing values.

3. **Exploratory Data Analysis**  
   - Line plot of closing price  
   - returns and return distribution

4. **Statistical Test (T-Test)**  
   - Compare mean returns between the first and second half of the year  
   - Use p-value to evaluate statistical significance

5. **Conclusions**  
   - We found that the returns are symetrical for both halves of the year
    - We found that the price almost doubled from January to December
   -

---

## Tools Used

- Python (Pandas, Matplotlib, Seaborn, SciPy)
- Jupyter Notebook
- Git & GitHub (for version control and sharing)

---
