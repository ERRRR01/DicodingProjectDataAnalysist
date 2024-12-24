# E-Commerce Dataset Analysis with Streamlit

## Overview

This project is a Streamlit web application that provides insights into an e-commerce dataset. It features two key visualizations:

1. **Top 5 Products with the Highest Purchases and Ratings Above 4:**
   - Identifies popular products with excellent ratings.
2. **Top Products by City:**
   - Highlights the most purchased product categories in the top 10 cities based on purchase count.

## Features

### Visualization 1: Top 5 Products with the Highest Purchases and Ratings Above 4

- Groups data by product category.
- Calculates the total purchases and average ratings for each product category.
- Displays a bar chart of the top 5 products with the highest purchase count and ratings above 4.

### Visualization 2: Top Products by City

- Groups data by city and product category.
- Identifies the most purchased product category in the top 10 cities by purchase count.
- Displays a bar chart with product categories color-coded by city.

### Conclusion Section

- Summarizes findings from the analysis.

## Requirements

### Libraries

- `pandas`: For data manipulation and analysis.
- `plotly.express`: For creating interactive visualizations.
- `streamlit`: For building the web application.

### Data

- The application uses two datasets:
  1. `Product_stok_kota_final.csv`: Contains information about product purchases, ratings, and city data.
  2. `product_favorit_akhir`: Derived from the same dataset for analyzing top-rated products.

## How to Run the Application

1. Clone the repository or download the project files.
2. Ensure the required libraries are installed. You can install them with:
   ```bash
   pip install pandas plotly streamlit
   ```
3. Place the dataset `Product_stok_kota_final.csv` in the same directory as the script.
4. Run the Streamlit application:
   ```bash
   streamlit run app.py
   ```
   Replace `<script_name>.py` with the name of the Python script.
5. Open the application in your browser. Streamlit will provide a local URL for access.

## Folder Structure

```
|-- Product_stok_kota_final.csv   # Input data file
|-- script_name.py               # Main Streamlit application
|-- README.md                    # Documentation file
```

## Notes

- Ensure the dataset contains the required columns: `product_category_name`, `review_score`, `order_item_id`, and `customer_city`.
- Large datasets might require additional memory or processing time.

## Insights Provided

1. **Top Products with High Purchases and Ratings:** Useful for identifying popular and well-rated products for marketing strategies.
2. **City-Based Product Insights:** Helps in demand forecasting and stock management by city.

## Conclusion

This Streamlit application provides a quick and interactive way to analyze e-commerce data. It helps in identifying trends and making data-driven decisions.
