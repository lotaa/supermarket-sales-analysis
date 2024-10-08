# Supermarket Sales Data Analysis
## Overview
    This project aims to explore and analyze supermarket sales data to uncover insights and patterns 
    that can help improve business performance. The key areas of focus include:

### The impact of tax on gross income.
  1. Analysis of customer satisfaction levels.
  2. Monthly gross income trends and their contributions to overall revenue.
### Data
    Dataset: The dataset used in this analysis includes the following columns:

    Invoice ID: Unique identifier for each transaction.
    Branch: The branch of the supermarket.
    City: The city where the branch is located.
    Customer type: Whether the customer is a member or a normal customer.
    Gender: Gender of the customer.
    Product line: The category of products purchased.
    Unit price: Price per unit of product.
    Quantity: Number of units purchased.
    Tax 5%: Tax applied at 5%.
    Total: Total amount including tax.
    Date: Date of the transaction.
    Time: Time of the transaction.
    Payment: Payment method (e.g., Cash, Credit Card).
    cogs: Cost of goods sold.
    gross margin percentage: Gross margin percentage.
    gross income: Income before taxes.
    Rating: Customer satisfaction rating (1-10).
## Methodology
      1.Data Cleaning: nothing to do 
      2. Data Preprocessing:  
                  ***Converted Date column to datetime format.***
                  ***Extracted month from the Date column to analyze trends over time.***
## Exploratory Data Analysis (EDA):
    
      1. Tax vs. Gross Income: Visualized the impact of tax on gross income using scatter plots and calculated correlations.
      2. Customer Satisfaction Levels: Grouped customer ratings into four satisfaction levels (Very Unsatisfied, Unsatisfied, Satisfied, Very Satisfied) and analyzed the impact of various factors like payment method, unit price, and quantity sold.
      3. Gross Income Trends: Analyzed gross income trends on a monthly basis, including the percentage contribution of each month to the total gross income.
## Visualization Tools:

      Used Matplotlib and Seaborn for creating detailed and informative charts.
      Visualizations include scatter plots, bar charts, box plots, and line plots.


## Key Findings
    1. Impact of Tax on Gross Income:
        A weak correlation between tax and gross income was observed, suggesting that the amount of tax does not significantly impact the gross income.
        Customer Satisfaction Analysis:
    
    2. Satisfaction levels were influenced by unit price, with lower prices generally corresponding to higher satisfaction.
        The method of payment and quantity purchased also played a role in determining satisfaction levels.
    
    3. Gross Income Trends:
        Monthly gross income showed clear trends with certain months contributing significantly more to the total revenue. 
        This could help in financial planning and promotional strategies.
## Visualizations

![download](https://github.com/user-attachments/assets/c03d7fb3-97f5-436b-8075-0210159526fb)


![download](https://github.com/user-attachments/assets/2ed6e820-986b-49d0-835b-145ea6bcef54)


![download](https://github.com/user-attachments/assets/acfb79c8-13eb-496c-ae4e-8876843514f2)


![download](https://github.com/user-attachments/assets/b43d3aa6-fcb8-4af2-934f-4b7243eac7e9)


![download](https://github.com/user-attachments/assets/cdf72345-6b88-4312-afc4-4e3f059a54a3)


