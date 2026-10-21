# Sales Data Analysis System

## Overview

The Sales Data Analysis System is a Python project designed to analyze sales data and generate meaningful business insights. It uses Pandas and NumPy to process sales records, calculate key performance metrics, and identify trends in product sales and revenue.

The project helps demonstrate how data analysis can support better business decision-making.

## Features

- Load and process sales data from CSV files.
- Calculate total revenue, total cost, and total profit.
- Calculate average revenue per transaction.
- Calculate the standard deviation of revenue.
- Identify products with the highest sales quantities.
- Identify products generating the highest revenue.
- Analyze revenue by date.
- Generate product-level statistical summaries.
- Display organized sales reports in the terminal.

## Technologies Used

- **Python** — Core programming language.
- **Pandas** — Data manipulation, grouping, and analysis.
- **NumPy** — Numerical calculations and statistical analysis.
- **CSV** — Data storage and input format.

## Project Structure

```text
Sales_data_analysis_system/
├── main.py
├── sales.csv
```

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/sales-data-analysis.git
```

### 2. Navigate to the project directory

```bash
cd Sales_data_analysis_system
```

If the cloned directory has a different name, navigate to that directory instead.

### 3. Install the required libraries

```bash
pip install pandas numpy
```

### 4. Run the program

```bash
python main.py
```

## Dataset

The project uses a CSV dataset containing sales transaction records.

Typical columns include:

- `OrderID` — Unique order identifier.
- `Date` — Date of the transaction.
- `Product` — Product sold.
- `Category` — Product category.
- `Quantity` — Number of units sold.
- `UnitPrice` — Selling price per unit.
- `UnitCost` — Cost per unit.

## Sample Analysis

The system can answer questions such as:

- Which product sold the most units?
- Which product generated the highest revenue?
- Which date had the highest revenue?
- What is the average revenue per transaction?
- How much profit did the business generate?
- How much variation exists in sales revenue?

## Learning Objectives

This project provides practical experience with:

- Reading CSV files using Pandas.
- Creating and manipulating DataFrames.
- Using `groupby()` and aggregation functions.
- Performing numerical calculations with NumPy.
- Applying descriptive statistics to business data.
- Organizing Python code into reusable components.

## Future Improvements

Potential enhancements include:

- Adding sales charts and visualizations using Matplotlib.
- Analyzing monthly and yearly sales trends.
- Exporting reports to Excel.
- Adding data validation and error handling.
- Building an interactive dashboard with Streamlit.
