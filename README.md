# DataAnalysis
# Sales Data Analysis

This project involves the analysis of sales data to identify key trends and insights. The analysis focuses on understanding the purchasing behavior of customers based on various demographic and socio-economic factors.

## Features

- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Visualization of key insights

## Requirements

- Python 3.12
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Installation

1. Clone the repository:
   
    git clone https://github.com/Srividhya09/DataAnalysis.git
   

2. Navigate to the project directory:
    
    cd DataAnalysis
    

3. Ensure you have all the required libraries installed. You can install them using pip:
    
    pip install pandas numpy matplotlib seaborn
  

4. Run the analysis script:
   
    Sales_Analysis.py
    

## Usage

- The script `Sales_Analysis.py` performs the following tasks:
  - Loads and preprocesses the sales data
  - Conducts exploratory data analysis
  - Visualizes the data to identify key insights

- The dataset `Sales Data.csv` should be placed in the same directory as the script.

## Data Analysis Steps

1. Importing Libraries
   - The necessary libraries for data manipulation, analysis, and visualization are imported.

2. Loading Data
   - The sales data is loaded into a DataFrame, handling any encoding issues.

3. Data Cleaning
   - Unrelated or blank columns are dropped.
   - Null values are checked and dropped.
   - Data types are changed as necessary.

4. Exploratory Data Analysis (EDA)
   - Descriptive statistics are generated for the data.
   - Bar charts and count plots are used to visualize the distribution of various features such as Gender, Age Group, State, Marital Status, Occupation, and Product Category.
   - Grouped data is used to plot total sales amounts and the number of orders.

5. Key Insights
   - Gender: Most buyers are females with greater purchasing power.
   - Age Group: Most buyers are females aged 26-35 years.
   - State: Most orders and total sales are from Uttar Pradesh, Maharashtra, and Karnataka.
   - Marital Status: Most buyers are married women.
   - Occupation: Most buyers work in IT, Healthcare, and Aviation sectors.
   - Product Category: Most sold products are from Food, Clothing, and Electronics categories.

6. Conclusion
   - Married women aged 26-35 from UP, Maharashtra, and Karnataka working in IT, Healthcare, and Aviation are more likely to buy products from Food, Clothing, and Electronics categories.

