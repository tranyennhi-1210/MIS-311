# Data Overview
The dataset represents transactional records from a supermarket chain with branches across three major cities: New York, Chicago, and Los Angeles. It captures details such as branch location, customer membership status, product categories, quantities purchased, and the total transaction price.
## Context: 
The data captures individual sale transactions, identifying where they occurred (Branch/City), who purchased them (Customer Type), and what was bought (Product Details).
## Dimensions: 
The raw dataset originally contained 242 rows and 8 columns.
## Attributes: 
sale_id: Unique identifier for each transaction.
branch & city: Geographical location of the sale.
customer_type: Classification of the shopper (Member vs. Normal).
product_name & product_category: Granular and high-level product classifications.
quantity & total_price: Numerical volume and monetary value of the sale.
## Columns: 
The attributes include sale_id, branch, city, customer_type, product_name, product_category, quantity, and total_price.
# Data Cleaning
## Missing Values: 
Initial data screening identified 12 missing values across the dataset. To maintain data integrity and ensure the accuracy of the subsequent analysis, a listwise deletion was performed, removing all rows containing incomplete information.
## Duplicate Rows: 
The dataset was further audited for redundancy. A total of 3 duplicate records were identified and removed. This step ensures that transaction totals and frequency counts are not artificially inflated.
## Final Count: 
After cleaning, the dataset contains 239 unique records.
# Descriptive Statistics
The following table summarizes the central tendencies and distribution of the numerical data (Quantity and Total Price) for the 239 transactions:
<img width="407" height="318" alt="image" src="https://github.com/user-attachments/assets/4b6a42cf-dc57-44e2-8e34-274e3d2fb284" />

## Key Insights
### Insight 1: Chicago and New York are currently the two strongest markets, while Los Angeles is significant weaker.
<img width="318" height="138" alt="image" src="https://github.com/user-attachments/assets/5269b07a-38ef-4575-9882-2d7f8b4df7c3" />
<img width="650" height="382" alt="image" src="https://github.com/user-attachments/assets/1ee5d769-40a9-46d9-8757-a56246a7d268" />
From the chart, we can see that Chicago and New York generated nearly equivalent revenue and both outpaced Los Angeles by approximately 15%-17%. 
Los Angeles may have some issues such as few high-value transactions, the product mix is not optimized or customers who spend less.
Business Action:
- Increase campaigns and promotions in Los Angeles.
- Check which categories are underperforming in Los Angeles to optimize inventory or prices.
### Insight 2:
