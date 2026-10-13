# Sales Data Filter & Report Engine

## Project Overview

This is a beginner-friendly Python project that uses NumPy to generate and analyze sales data for 10 stores across 12 months.

The project demonstrates how NumPy arrays can be used to filter sales records, compare store performance, analyze quarterly sales, and create monthly sales targets.

## Objectives

- Generate sales data for 10 stores over 12 months.
- Calculate monthly, quarterly, and store-wise sales totals.
- Identify the best and lowest-performing months and stores.
- Filter data using Boolean masks and combined conditions.
- Select specific stores using fancy indexing.
- Generate monthly growth targets using `np.linspace()`.

## Technologies Used

- Python
- NumPy
- Google Colab

## NumPy Concepts Used

- `np.array()` — create arrays
- `np.arange()` — create month numbers
- `np.random.randint()` — generate sample sales data
- `reshape()` — arrange sales into 10 rows and 12 columns
- Array slicing — select quarterly sales
- Boolean masking — filter sales based on conditions
- `&`, `|`, `~` — combine or reverse conditions
- Fancy indexing — select specific store rows
- `np.argmax()` and `np.argmin()` — find maximum and minimum values
- `np.argsort()` — identify the top three sales months
- `np.linspace()` — create monthly growth targets

## How to Run

1. Open the notebook `Sales_Data_Filter_Report_Engine.ipynb` in Google Colab.
2. Run the code cells from top to bottom.
3. Review the monthly, quarterly, and store-wise reports.
4. Check the Boolean filtering results and growth-target report.

## Data

The project uses randomly generated sample sales data. It does not use real business or customer records.

## Conclusion

This project helped me practice NumPy arrays, slicing, Boolean masking, fancy indexing, and basic sales reporting through a practical example.
