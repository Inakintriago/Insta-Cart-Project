# 🛒 Insta-Cart

## 📝 Context
Instacart is a grocery delivery platform that allows customers to place orders online and have them delivered to their homes, similar to services like Uber Eats or Door Dash.  
The goal of this project is to analyze a reduced and modified dataset from Instacart, preserving the distribution of the original data, to better understand customer purchasing patterns.

## 🛠️ Tools Used
- **Python**: Data analysis and preprocessing.
- **Pandas** and **NumPy**: Data manipulation and cleaning.
- **Matplotlib** and **Seaborn**: Data visualization.
- **Jupyter Notebook**: Documenting the workflow.

## 📈 Results Analysis
The project was developed in three main steps:
1. **Data Description**: The structure and content of five files (`instacart_orders.csv`, `products.csv`, `order_products.csv`, `aisles.csv`, `departments.csv`) were reviewed, identifying primary keys and relationships between tables.
   
2. **Data Preprocessing**: 
   - Duplicates were removed and missing values were handled.
   - Tables were integrated for consolidated analysis of orders, products, aisles, and departments.

3. **Data Analysis**:
   - Graphs and tables were generated to visualize:
     - Most popular products.
     - Purchase times and frequencies (by day of the week and time of day).
     - Product reorder patterns.

## 📋 Conclusions
- Data cleaning was crucial to ensure reliable and meaningful analysis.
- The most in-demand products and reorder patterns were identified, providing valuable insights into customer loyalty and purchasing preferences.
- The results help the company better understand user behavior and optimize inventory and marketing strategies.
