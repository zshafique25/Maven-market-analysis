# Maven-Market-Analysis

## Project Overview
This project aims to provide insights into the operations and customer behavior of Maven Market, a multinational grocery chain with locations in Canada, Mexico, and the United States. The primary objectives were to:
- Optimize inventory management
- Enhance marketing strategies
- Improve overall business performance  
The project leverages data from various sources including sales records and customer demographics.

## Methodology

1. **Connecting and Shaping the Data**:
   - Data was loaded from multiple sources including sales records, returns records, customer records, inventory, and stores.
   - Extract, Transform, Load (ETL) processes were employed to clean and integrate the data.
   - Data cleansing techniques were applied to handle missing values, duplicates, and inconsistencies.

2. **Building a Relational Model**:
   - A relational database model was constructed to organize the integrated data.
   - Tables were created for customers, products, sales transactions, and inventory.
   - Relationships between tables were established.
![Databasemodel](https://github.com/zshafique25/Maven-market-analysis/blob/master/databasemodel.PNG)

3. **Adding Calculated Fields**:
   - Additional fields were calculated to derive meaningful insights using Data Analysis Expressions (DAX).
   - Metrics such as total profit, total revenue, and product popularity were computed to aid decision-making.

4. **Designing an Interactive Report**:
   - An interactive report was designed to present key findings and allow stakeholders to explore the data.
   - Visualization tools such as charts and graphs were utilized for intuitive data representation.
   - User-friendly interfaces were developed to enable easy navigation and customization of reports.

## Report

1. **Topline Performance**:  
   ![Topline Performance](https://github.com/zshafique25/Maven-market-analysis/blob/master/Toplineperformance.PNG)

   - Provides a comprehensive overview of Maven Market's performance metrics for the current month.
   - Displays key indicators such as profit, transactions, and returns, alongside customer demographics and order distribution.
   - Highlights the top 30 brands for inventory restocking, tracks weekly revenue trends, and compares actual revenue to targets.

2. **Drillthrough Product Details**:  
   ![Drillthrough Product Details](https://github.com/zshafique25/Maven-market-analysis/blob/master/Productdetails.PNG)

   - Offers a detailed view of product sales trends, targets, and pricing dynamics.
   - The product metrics selection slicer allows customization based on specific metrics.
   - The price range slicer enables toggling between different price ranges to identify optimal pricing strategies.

3. **Customer Details**:  
   ![Customer Details](https://github.com/zshafique25/Maven-market-analysis/blob/master/customerdetails.PNG)

   - Provides insights into customer demographics, purchasing behavior, and loyalty patterns.
   - Customer segmentation based on location, occupation, and yearly income to tailor marketing strategies.
   - Information on the top 100 customers ranked by revenue to target engagement and personalized offerings.

## Tools
- Microsoft Power BI

## Conclusion
The data analysis project has yielded valuable insights into Maven Market's operations and customer behavior. Through data-driven decision-making, Maven Market is well-positioned to:
- Optimize inventory management
- Enhance marketing strategies
- Drive overall business growth
  
The interactive reports developed serve as powerful tools for stakeholders, enabling actionable insights and informed decisions. Continuous monitoring and analysis will be essential for maintaining competitiveness and adapting to market dynamics.
