# 🗂️ **Data Overview**
The dataset represents transactional records from a supermarket chain with branches across three major cities: New York, Chicago, and Los Angeles. It captures details such as branch location, customer membership status, product categories, quantities purchased, and the total transaction price.
## Context: 
The data captures individual sale transactions, identifying where they occurred (Branch/City), who purchased them (Customer Type), and what was bought (Product Details).

## Dimensions: 
The raw dataset originally contained 242 rows and 8 columns.

## Attributes: 
- sale_id: Unique identifier for each transaction.
- branch & city: Geographical location of the sale.
- customer_type: Classification of the shopper (Member vs. Normal).
- product_name & product_category: Granular and high-level product classifications.
- quantity & total_price: Numerical volume and monetary value of the sale.
  
## Columns: 
The attributes include:
- sale_id
- branch
- city
- customer_type
- product_name
- product_category
- quantity
- total_price

#⚙️ **Data Cleaning**
## Missing Values: 
Initial data screening identified 12 missing values across the dataset. To maintain data integrity and ensure the accuracy of the subsequent analysis, a listwise deletion was performed, removing all rows containing incomplete information.
## Duplicate Rows: 
The dataset was further audited for redundancy. A total of 3 duplicate records were identified and removed. This step ensures that transaction totals and frequency counts are not artificially inflated.
## Final Count: 
After cleaning, the dataset contains 239 unique records.
# Descriptive Statistics
The following table summarizes the central tendencies and distribution of the numerical data (Quantity and Total Price) for the 239 transactions:
<img width="407" height="318" alt="image" src="https://github.com/user-attachments/assets/4b6a42cf-dc57-44e2-8e34-274e3d2fb284" />

##💡**Key Insights**

### Insight 1: Chicago and New York are currently the two strongest markets, while Los Angeles is significant weaker.
<img width="318" height="138" alt="image" src="https://github.com/user-attachments/assets/5269b07a-38ef-4575-9882-2d7f8b4df7c3" />

<img width="644" height="373" alt="image" src="https://github.com/user-attachments/assets/b45057c8-519d-46b7-a7e8-0e06b306357c" />

From the chart, we can see that Chicago and New York generated nearly equivalent revenue and both outpaced Los Angeles by approximately 15%-17%. 
Los Angeles may have some issues such as few high-value transactions, the product mix is not optimized or customers who spend less.

**Business Action:**
- Increase campaigns and promotions in Los Angeles.
- Check which categories are underperforming in Los Angeles to optimize inventory or prices.

### Insight 2:Shampoo and Notebook are two products that generate the most revenue.
<img width="308" height="187" alt="image" src="https://github.com/user-attachments/assets/9f643075-71ea-4a4a-a551-5eb424cf7f56" />

<img width="575" height="312" alt="image" src="https://github.com/user-attachments/assets/1f5174de-118a-48b4-bb18-134bf5df6492" />

From the chart above, Shampoo and Notebook are core products of business. These products significant outsold the others, meaning the stable demand or the order value is higher than the average.

<img width="334" height="537" alt="image" src="https://github.com/user-attachments/assets/5b9328d0-5714-4887-ba4e-34811b9ebadc" />
<img width="655" height="369" alt="image" src="https://github.com/user-attachments/assets/bf3ee039-5d85-4eee-afb8-02afcc40e2b5" />

Especially, Notebooks are selling extremely well in New York (about 2.825) and Orange Juices is the strongest in Chicago (with 2,600) -> There is difference in preferences by city.

**Business Action:**
- Prioritize stock for Shampoo and Notebook.
- It is possible to run a localized promotion:
  + Notebook in New York
  + Orange Juices in Chicago
 
#🧩**Conclusion**
Analysis of supermarket sales data reveals that business is being driven by key urban markets and "core" products, highlighting clear opportunities for regional optimization.
Chicago and New York are currently the two leading revenue generators with stability and high market penetration. Conversely, the Los Angeles market shows a significant decline, indicating a pressing need for localized marketing strategies and a reassessment of product portfolio suitability in this region.
Shampoo and Notebooks are identified as the two core revenue-generating products. The data also reveals distinct geographical preferences are New York prioritizes stationery (notebooks), while Chicago has a strong preference for beverages (Orange Juice).
**Strategic direction:** To maximize profits, businesses should shift from a general approach to a localized promotion and inventory management strategy. By securing supplies for core products and implementing city-specific campaigns (e.g., notebook promotions in New York), supermarkets can optimize their supply chain and improve conversion rates across all branches.
