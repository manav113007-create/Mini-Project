# Mini Project 
# Electronics Product Sales Data Analysis

Cleans a US electronics sales dataset (2019), analyses it with Pandas, draws charts with Matplotlib and Seaborn, and shows the results on an interactive webpage.

## Files

| File | Purpose |
|---|---|
| `Updated_sales.csv` | Raw sales data |
| `A5_B3_B4_SL_Project_.ipynb` | Notebook: cleaning, analysis, charts |
| `summary_tables.xlsx` | Summary tables exported from the notebook |
| `index.html`, `style.css` | Presentation webpage |

## Workflow

1. Load and inspect the CSV
2. Clean: blank rows, duplicates, date formats
3. Create `Revenue = Price Each x Quantity Ordered`
4. Group, rank and summarise with Pandas
5. Visualise with Matplotlib and Seaborn

## Key results

- 30,206 clean rows, 19 products, 9 cities
- Total revenue: about $5.64M
- Top product: Macbook Pro Laptop
- Top city: San Francisco (about 24% of revenue)
- Busiest hours: around 12 PM and 7 PM

## How to run

**Notebook:** open the `.ipynb` in Google Colab or Jupyter, put `Updated_sales.csv` in the same folder (change the path in the first cells if needed), then run all cells.

**Webpage:** keep `index.html` and `style.css` in the same folder and open `index.html` in a browser.

## Tools

Python, Pandas, NumPy, SciPy, Matplotlib, Seaborn, HTML, CSS, JavaScript

## Notes
- The scraping cells at the end of the notebook do not run as written (unquoted URL; Kaggle needs sign-in).
- Webpage numbers are copied from the notebook results and must be updated by hand if the data changes.
