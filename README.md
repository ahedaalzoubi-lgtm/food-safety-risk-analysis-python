# Food Safety Risk Analysis Using Python

This project uses Python to analyze food inspection data and identify patterns related to failed inspections, violation frequency, inspection risk levels, and corrective-action priorities.

## Project Objective

The objective of this project is to explore food inspection data and create a practical priority view that can support compliance monitoring and corrective-action planning.

## Key Questions

- Which food business groups are most associated with failed inspections?
- Which groups have higher fail rates?
- Do high-risk inspections have more violations?
- How does inspection activity change over time?
- Which facilities should be prioritized for follow-up?

## Tools Used

- Python
- pandas
- NumPy
- matplotlib
- Jupyter Notebook

## Main Steps

- Loaded and inspected the dataset
- Cleaned and prepared date and text fields
- Grouped inspection results into compliance categories
- Grouped inspection risk levels into High, Medium, Low, and Unknown
- Created violation indicators and violation counts
- Grouped facility types into broader food business groups
- Performed exploratory data analysis
- Created charts to show inspection results, fail rates, violations, and monthly trends
- Built a simple rule-based priority score for corrective-action planning

## Dataset

This project uses a public food inspection dataset.

The dataset file is not included in this repository because of file-size limitations.

To run the notebook locally, download the dataset and place it in the same folder as the notebook with this filename:

`Chicago_Food_Inspections_2023_present.csv`

## Project Note

This project is not intended to be a predictive model. It is a practical beginner-friendly Python analysis that demonstrates data cleaning, feature engineering, exploratory data analysis, visualization, and simple scoring logic in a food safety context.
