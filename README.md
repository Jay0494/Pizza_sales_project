# Pizza_sales_project
![pizza](https://github.com/user-attachments/assets/7d8c7935-71c2-485a-819a-1b5d371036b7)

## **Data Analysis Portfolio: Pizza Company Sales Analysis**

### **Project Overview**
This project involved migrating and analyzing sales data for a UK-based pizza company. The primary objective was to extract insights that would help management understand the company's sales performance across various metrics, including best-selling pizzas, the most demanded categories and sizes, sales trends, and the relationship between sales and quantities sold. The analysis was conducted using MySQL for data management and Power BI for data visualization.

### **Tools Used**
- **MySQL**: For data migration, cleaning, and retrieval through SQL queries.
- **Power BI**: For data visualization and reporting.
- **Power Query**: For further data transformation and cleaning in Power BI.

### **Data Preparation**
1. **Data Migration**: The data, initially stored in CSV format on Kaggle, was imported into a MySQL database, consisting of four tables.
2. **Data Cleaning**: Inaccurate data types were corrected, and data was standardized to ensure consistency.
3. **Data Retrieval**: Inner joins were used to combine tables and retrieve necessary columns for analysis.
4. **Further Cleaning in Power BI**:
   - Renamed column headers for clarity.
   - Standardized data formatting.
   - Removed duplicates to ensure data quality.
   
### **Analysis & Insights**
![pizza 1](https://github.com/user-attachments/assets/18e522f3-072a-4f67-ac3f-3fa5b43caafe)

#### **Revenue Overview**
- Total revenue from January to December 2015: **£817,860.05**
- Total pizzas sold: **49,574**

#### **Category Performance**
- **Revenue by Category**:
  - Classic: **£220,053.10**
  - Supreme: **£208,197.00**
  - Chicken: **£195,919.50**
  - Veggie: **£193,690.45**
  ![pizza 2](https://github.com/user-attachments/assets/90844a25-b576-4840-9c67-3f5876156113)

- **Quantity Sold by Category**:
  - Classic: **14,888 pizzas**
  - Supreme: **11,987 pizzas**
  - Veggie: **11,649 pizzas**
  - Chicken: **11,050 pizzas**
![pizza 3](https://github.com/user-attachments/assets/c26e8d38-cd2e-4dfd-b049-3782aa393504)

#### **Pizza Size Demand**
- Large: **18,956 pizzas**
- Medium: **15,635 pizzas**
- Small: **14,403 pizzas**
- Extra Large: **552 pizzas**
- Super Size: **28 pizzas**

#### **Top 10 Revenue-Generating Pizzas**
1. Thai Chicken Pizza
2. Barbeque Chicken Pizza
3. California Chicken Pizza
4. Classic Deluxe Pizza
5. Spicy Italian Pizza
6. Southwest Chicken Pizza
7. Italian Supreme Pizza
8. Hawaiian Pizza
9. Four Cheese Pizza
10. Sicilian Pizza

#### **Sales Trends**
- **Quarterly Sales**:
  - Q1: 12,454 pizzas sold, **£205.4k** in revenue.
  - Q2: 12,586 pizzas sold, **£208.4k** in revenue.
  - Q3: 12,450 pizzas sold, **£205k** in revenue.
  - Q4: 12,084 pizzas sold, **£199.1k** in revenue.

- **Monthly Sales**:
  - **Peak Sales**: July and May.
  - **Lowest Sales**: September and October.


#### **Correlation Analysis**
- The correlation coefficient between sales and quantity sold is **0.93**, indicating a strong positive relationship.
![pizza 4](https://github.com/user-attachments/assets/7edf15ba-175a-4f63-89dc-0c81fda91ce5)

### **Conclusion**
The analysis highlights that the company’s best-performing category in terms of both revenue and quantity is the Classic pizza. Large-sized pizzas are the most popular among customers, significantly outpacing other sizes. Seasonal sales trends suggest a need to focus marketing efforts in the months of September and October, where sales are the lowest. The high correlation between sales and quantity sold suggests that strategies to increase quantity sold could directly impact overall revenue.

### **Recommendations**
1. **Focus on Promoting Top-Selling Pizzas**: Highlight the best-sellers in marketing campaigns to drive further sales.
2. **Enhance Product Offering Around Popular Sizes**: Consider special deals for large and medium sizes to boost sales.
3. **Seasonal Campaigns**: Launch targeted promotions during September and October to counteract the dip in sales during these months.
4. **Explore New Product Offerings**: Introduce limited-time variations of top-selling pizzas to maintain customer interest and drive sales growth.

### **Next Steps**
- Use insights to refine marketing strategies and product offerings.
- Monitor sales performance regularly using Power BI dashboards.
- Conduct further analysis to explore new customer segments and product innovations.

---
