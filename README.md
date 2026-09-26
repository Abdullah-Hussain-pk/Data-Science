# Sales Data Analysis 
## Overview
This project performs an end-to-end exploratory data analysis on a retail sales
dataset using Python. It covers data loading, cleaning, statistical analysis,
and visualization, concluding with a generated summary report.

## Tools & Libraries
- Python (Jupyter Notebook)
- pandas — data manipulation and cleaning
- NumPy — numerical operations
- Matplotlib — data visualization

## Dataset
`sample_data.csv` contains sales records with the following columns:
- **Date** — transaction date
- **Product** — item sold
- **Category** — product category (Electronics, Furniture, Apparel, Appliances, Stationery)
- **Region** — sales region (North, South, East, West, Central)
- **Units** — quantity sold
- **Amount** — revenue generated (in Rs)

## Analysis Steps
1. **Data Loading & Inspection** — shape, data types, missing values, summary statistics
2. **Data Cleaning** — dropped missing values, removed duplicates, converted date fields
3. **Exploratory Analysis** — total/average/median revenue, top products, product frequency
4. **Visualization**
   - Bar chart: Top 10 products by revenue
   - Line chart: Monthly sales trend across the year
   - Pie chart: Sales distribution by region
5. **Category Analysis** — revenue and units sold grouped by category
6. **Summary Report** — key metrics compiled into `report.txt`

## Key Findings
- Total revenue, top-performing products, and the best-performing month are
  calculated and printed in the final report.
- Electronics (Laptops, Smartphones) drive the largest share of revenue.
- Sales show a seasonal uptick toward the end of the year (Nov–Dec).

## Files
- `sales_analysis.ipynb` — full analysis notebook
- `sample_data.csv` — sales dataset used
- `report.txt` — generated summary report

## How to Run
1. Install dependencies: `pip install pandas numpy matplotlib jupyter`
2. Open `sales_analysis.ipynb` in Jupyter or VS Code
3. Run all cells
