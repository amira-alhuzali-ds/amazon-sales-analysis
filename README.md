# Amazon Sales Data: Preprocessing and Analysis

A team project from the Data Science program at Umm Al-Qura University (College of Computing, team of 4 students, 2026). It cleans, explores, and prepares an Amazon product dataset (1,465 records) using Python.

## What the notebook covers

| Section | Topic |
|---|---|
| 1 | Data loading and inspection |
| 2 | Data quality assessment |
| 3A | Data cleaning (type conversion, missing values, duplicates, category cleanup) |
| **3B** | **Exploratory data analysis (EDA)** |
| 4 | Outlier detection and handling |
| 5 | Data transformation (feature scaling) |
| 6 | Feature engineering |
| 7 | Analysis and results (RFE feature selection and PCA) |

Explanations in the notebook are written in English and Arabic.

## My contribution

I worked on **Section 3, Part B: Exploratory Data Analysis**:

- Summary statistics (`describe`, category frequencies) after reducing the hierarchical category column to the 10 most frequent middle-level categories.
- Aggregation by category with `groupby` and `pivot_table` (average rating, discounted price, discount percentage).
- Visualizations: rating histogram, discounted-price box plot, category bar plot, correlation heatmap, and price vs. rating scatter plot.

The other sections were done by my teammates.

## Tools

Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Google Colab.

## Running it

The notebook expects a file named `amazon.csv` (the Amazon Sales dataset from Kaggle) in the same folder. The dataset is not included in this repository; download it from its original source. Then open `Amazon_Sales_Analysis.ipynb` in Jupyter or Google Colab and run the cells in order.

## Notes

- This is an academic project. Findings describe this dataset only.
- Student names and IDs were removed from the published notebook.
