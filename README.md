# Sales Data Analysis

## Project Overview

This project explores sales transaction data using Python. It analyzes revenue across months, products, and regions to summarize sales performance and identify patterns in the dataset.

## Objectives

- Inspect and validate the dataset.
- Check for missing values, duplicate records, and invalid values.
- Calculate transaction-level revenue, total revenue, and units sold.
- Analyze monthly revenue patterns.
- Compare product and regional performance.
- Visualize results and document the limitations of the analysis.

## Tools and Technologies

- Python
- Pandas
- Matplotlib
- Jupyter Notebook

## Dataset

The dataset, `sales_data.csv`, contains 8 transactions recorded between January and April 2024.

The columns include:

- `Order Date`: Date of the transaction.
- `Product`: Product sold.
- `Quantity`: Number of units sold.
- `Price`: Price per unit.
- `Region`: Region associated with the transaction.

## Key Findings

- **Total revenue:** ₹550,000 across 8 transactions.
- **Total units sold:** 17.
- **Monthly performance:** April recorded the highest revenue at ₹170,000, while February recorded the lowest at ₹80,000.
- **Product performance:** Laptops generated the highest revenue at ₹300,000. Mobiles had the highest unit sales, with 8 units.
- **Regional performance:** East and North tied for the highest revenue at ₹180,000 each. West recorded the lowest revenue at ₹70,000.

## Limitations

- The dataset contains only 8 transactions over four months.
- The results describe this dataset and may not represent broader sales patterns.
- Costs and expenses are not provided, so profit cannot be calculated.
- The analysis does not establish the causes of changes in revenue.
- A larger dataset covering a longer period would be needed for stronger conclusions.

## How to Run

1. Download or clone this repository.
2. Install Python and Jupyter Notebook or JupyterLab.
3. Install the required libraries:

   ```bash
   pip install pandas matplotlib jupyter
   ```

4. Open `sales_analysis.ipynb` in Jupyter.
5. Run the notebook cells from beginning to end.

## Conclusion

This project demonstrates a basic exploratory data analysis workflow, including data validation, feature engineering, summary statistics, visualization, and interpretation of results. The findings are limited to the small dataset provided.
