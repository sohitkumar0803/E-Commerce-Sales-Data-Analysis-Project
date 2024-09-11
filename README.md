

# E-Commerce Sales Data Analysis Project

## Overview
This project involves analyzing sales data from two tables: Orders and Details. The analysis is performed using Python in a Jupyter Notebook, with a focus on customer behavior, geographical trends, product performance, order analysis, payment modes, profitability, and time series analysis.

## Data Description
- **Orders Table**: Contains columns for Order ID, Order Date, Customer Name, State, and City.
- **Details Table**: Contains columns for Order ID, Amount, Profit, Quantity, Category, Sub-Category, and Payment Mode.

## Analysis Steps
1. **Environment Setup**: Install necessary libraries.
2. **Data Loading**: Load data from CSV files into pandas DataFrames.
3. **Data Merging**: Merge Orders and Details tables on Order ID.
4. **Data Exploration**: Get an overview of the data.
5. **Data Cleaning**: Handle missing values.
6. **Data Visualization**: Create visualizations to gain insights.
7. **Further Analysis**: Perform specific analyses based on goals.
8. **Save Results**: Save important results and visualizations.

## Questions Addressed
### 1. Customer Analysis
- **Top Customers by Total Amount Spent**
- **Average Order Value per Customer**
- **Patterns in Customer Purchasing Behavior**

### 2. Geographical Analysis
- **States and Cities with Highest Sales and Profits**
- **Regional Trends in Product Categories or Payment Modes**

### 3. Product Analysis
- **Sub-Categories with Highest Quantity Sold**
- **Profit Margin for Each Category and Sub-Category**
- **Seasonal Trends in Product Sales**

### 4. Order Analysis
- **Average Order Size**
- **Order Size by Category and Sub-Category**
- **Distribution of Order Dates**

### 5. Payment Mode Analysis
- **Payment Modes with Higher Average Order Values**
- **Trends in Payment Mode Preferences Over Time**

### 6. Profitability Analysis
- **Overall Profit Margin**
- **Profit by Order Size, Category, and Sub-Category**
- **Loss-Making Categories or Sub-Categories**

### 7. Time Series Analysis
- **Monthly and Yearly Sales Trends**
- **Sales and Profit Over Time**
- **Sales and Profit by Day of the Week or Month**

### 8. Customer Segmentation
- **Segment Customers Based on Purchasing Behavior**
- **Characteristics of Each Customer Segment**

## Visualizations
The project includes various visualizations to illustrate the insights gained from the data analysis:
- Bar plots for top customers, states, cities, sub-categories, and payment modes.
- Line plots for sales trends over time.
- Histograms for distributions of order values and dates.
- Box plots for profit by category.

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/sohitkumar0803/E-Commerce-Sales-Data-Analysis-Project.git
   ```
2. Navigate to the project directory:
   ```bash
   cd E-Commerce-Sales-Data-Analysis-Project
   ```
3. Install the required libraries:
   ```bash
   pip install pandas matplotlib seaborn
   ```
4. Open the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
5. Run the notebook cells to perform the analysis.

## Conclusion
This project provides a comprehensive analysis of sales data, offering insights into customer behavior, geographical trends, product performance, and more. The visualizations and analyses can help in making informed business decisions.

## License

[MIT](https://choosealicense.com/licenses/mit/)

