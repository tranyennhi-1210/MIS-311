# Data Overview
## Source and Context: 
The dataset represents transactional records from a supermarket chain with branches across three major cities: New York, Chicago, and Los Angeles. It captures details such as branch location, customer membership status, product categories, quantities purchased, and the total transaction price.
## Dataset Dimensions: 
The original dataset consists of 242 rows and 8 columns.
## Columns: 
The attributes include sale_id, branch, city, customer_type, product_name, product_category, quantity, and total_price.
# Data Cleaning
## Missing Values: 
Initial data screening identified 12 missing values across the dataset. To maintain data integrity and ensure the accuracy of the subsequent analysis, a listwise deletion was performed, removing all rows containing incomplete information.
## Duplicate Rows: 
The dataset was further audited for redundancy. A total of 3 duplicate records were identified and removed. This step ensures that transaction totals and frequency counts are not artificially inflated.
## Final Count: 
After cleaning, the dataset contains 239 unique records.
## Final Data Integrity: 
Following the removal of incomplete and redundant entries, the dataset was validated as clean and ready for analysis. The final refined dataset consists of 227 high-quality records.
# Descriptive Statistics
The following table summarizes the central tendencies and distribution of the numerical data (Quantity and Total Price) for the 239 transactions:
<img width="407" height="318" alt="image" src="https://github.com/user-attachments/assets/4b6a42cf-dc57-44e2-8e34-274e3d2fb284" />
