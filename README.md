# Coffee Shop Sales Analysis

This project involves an in-depth analysis of coffee shop sales data using Excel.

## Objective

Analyze the sales data to identify trends and insights that can help improve business performance.

## Dataset Columns

- **transaction_id:** Unique sequential ID representing an individual transaction
- **transaction_date:** Date of the transaction (MM/DD/YY)
- **transaction_time:** Timestamp of the transaction (HH:MM:SS)
- **transaction_qty:** Quantity of items sold
- **store_id:** Unique ID of the coffee shop where the transaction took place
- **store_location:** Location of the coffee shop where the transaction took place
- **product_id:** Unique ID of the product sold
- **unit_price:** Retail price of the product sold
- **product_category:** Description of the product category
- **product_type:** Description of the product type
- **product_detail:** Description of the product detail

## Project Tasks

1. **Understanding the Business Problem**
2. **Data Cleaning and Transformation**
3. **Pivot Tables and Charts**

### Analysis and Visualization

1. **Peak transaction quantity Hours**
   - **Pivot Table:** Rows - Transaction Time (Hour), Columns - None, Values - Count of transaction quantity
   - **Chart:** Line chart showing peak transaction quantity order hours during the day.

2. **Total Sales by Product Category**
   - **Pivot Table:** Rows - Product Category, Columns - None, Values - Sum of Total_bill
   - **Chart:** Pie chart showing total sales for each product category.

3. **Size Distribution based on orders**
   - **Pivot Table:** Rows - Size, Columns - None, Values - count of transaction_id
   - **Chart:** Pie chart distribute total orders by size.
   
4. **Sales Performance by Store Location**
   - **Pivot Table:** Rows - Store Location, Columns - None, Values - Sum of total_bill
   - **Chart:** Bar chart comparing sales performance across different store locations.
   
5. **Top Selling Products**
   - **Pivot Table:** Rows - Product Detail, Columns - None, Values - Sum of total_bill
   - **Chart:** Bar chart showing top-selling products based on sales revenue.
   
6. **Order Value by Day of the Week**
   - **Pivot Table:** Rows - Transaction Date (Day of the Week), Columns - None, Values - count of transaction_id
   - **Chart:** Bar chart showing order value for each day of the week.

## Dashboard

![Screenshot (33)](https://github.com/user-attachments/assets/fc3ecfcf-e4b3-461b-b08b-bd65e4ad02f4)

### Key Insights

1. **Quantity Ordered Based on Hours:**
   - Peak sales hours are between 3 PM and 5 PM, indicating high afternoon customer.

2. **Category Percentage Distribution Sales:**
   - The majority of sales come from Coffee (39%), followed by Tea (28%) and Bakery items (12%).

3. **Size Distribution based on orders**
   - The majority of orders from large size (30%), followed by Regular size (31%) and small size (9%).

4. **Footfall Over Various Store Locations:**
   - The Hell's Kitchen location has the highest footfall, followed by the Astoria and Lower Manhattan locations.

5. **Top 5 Products Based on Sales:**
   - The best-selling product is Barista Espresso, followed by  Brewed Chai Tea, Hot Chocolate, Gourmet Brewed Coffee, and Brewed Black Tea.

6. **Order on Weekdays:**
   - Sales are consistently high on weekdays, with a slight drop on weekends, particularly on Saturday.

