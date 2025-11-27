# Task 5: Data Analysis on CSV File using Python

## Objective
The objective of this task is to analyze a sales dataset stored in a CSV file using Python and Pandas, and to visualize meaningful insights using Matplotlib.

---

## Tools & Technologies Used
- Python 3
- Pandas
- Matplotlib
- Visual Studio Code

---

## Project Files
- `sales_data.csv` – CSV file containing sales data  
- `analyze.py` – Python script used for analysis  
- `README.md` – Project documentation  

---

## Dataset Description
The CSV file (`sales_data.csv`) contains the following columns:

| Column Name | Description |
|------------|-------------|
| Date | Date of the sale |
| Product | Name of the product |
| Quantity | Number of units sold |
| Price | Price per unit |

---

## Steps Performed in the Code
1. Imported required libraries (`pandas` and `matplotlib`).
2. Loaded the CSV file using `pd.read_csv()`.
3. Displayed basic information using `info()` and `head()`.
4. Created a new column **Total_Sales** by multiplying Quantity and Price.
5. Grouped data by Product and calculated total sales.
6. Visualized total sales using a bar chart.
7. Converted Date column to datetime format.
8. Analyzed daily sales trends using a line chart.
9. Displayed key insights such as highest-selling product and total revenue.

---

## Output & Visualizations
- Bar Chart: Total Sales by Product  
- Line Chart: Daily Sales Trend  
- Printed summaries and insights in the terminal.

---

## Key Insights
- Pen is the highest-selling product.
- Notebook contributes significantly to revenue.
- Sales trend is consistent across days.
- Low-cost items contribute steadily to total revenue.

---

## How to Run the Project
1. Open the project folder in Visual Studio Code.
2. Install required libraries:
   ```
   pip install pandas matplotlib
   ```
3. Run the script:
   ```
   python analyze.py
   ```

---

## Result
Successfully performed data analysis on a CSV file using Python and generated insights using visualizations.

---

## Author
Task completed as part of Task 5 – Data Analysis Assignment / Internship Task.
