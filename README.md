# Nexusgoods E-commerce Analysis

This project analyzes the Nexusgoods e-commerce datasets in a Jupyter notebook to answer business questions about sales, delivery performance, payments, ratings, and regional trends.

## Project Files

- `project.ipynb`: Main analysis notebook.
- `requirement.txt`: Python dependencies.
- `Nexusgood_geolocation_dataset.csv`: Geolocation reference data.
- `Nexusgoods_customers_dataset .csv`: Customer information (note the space before `.csv` in filename).
- `Nexusgoods_order_items_dataset.csv`: Order line items and prices.
- `Nexusgoods_order_payments_dataset.csv`: Payment methods and payment values.
- `Nexusgoods_order_reviews_dataset.csv`: Review scores and comments.
- `Nexusgoods_orders_dataset (1).csv`: Order lifecycle timestamps and status.
- `Nexusgoods_products_dataset.csv`: Product metadata and dimensions.
- `Nexusgoods_sellers_dataset.csv`: Seller location information.
- `product_category_name_translation.csv`: Category translation to English.

## Analysis Covered in Notebook

The notebook includes these tasks:

1. Top 10 product categories by total sales value.
2. Delayed order analysis by category.
3. Payment method usage distribution.
4. Top 10 and bottom 10 products by average review score.
5. State-wise sales performance (high vs low sales states).

## Requirements

- Python 3.9+
- Jupyter Notebook or VS Code Notebook support

Install dependencies:

```bash
pip install -r requirement.txt
```

Dependencies listed in `requirement.txt`:

- pandas
- numpy
- matplotlib
- scikit-learn
- ipykernel

## How to Run

1. Open `project.ipynb` in VS Code or Jupyter.
2. Make sure the kernel uses the environment where dependencies are installed.
3. Run cells from top to bottom.
4. Verify all CSV files are in the same directory as the notebook.

## Notes

- The notebook expects specific filenames, including:
  - `Nexusgoods_customers_dataset .csv` (contains an intentional space before `.csv`).
  - `Nexusgoods_orders_dataset (1).csv`.
- Date parsing in the notebook uses `%d-%m-%Y %H:%M` format for order timestamp fields.

