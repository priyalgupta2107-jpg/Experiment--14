# Experiment-14
## Aim of Experiment:  Data binning and Data Formatting using Python
## Theory:
a) Data Binning → process of grouping continuous numerical data into different categories (bins) to make it easier to understand and analyze.  
- It helps in reducing complexity by converting large ranges of values into a few meaningful groups.  
- Example → marks can be grouped as Low, Medium, High instead of exact values.  
- In Python, pd.cut() is used to divide data into bins and assign labels.  

b) Data Formatting → process of changing data into a standard and consistent format for better analysis.    
- It includes converting data types (int, float, string) and modifying text format.    
- Helps in making data clean, uniform, and easy to process.    
- Example → converting text to uppercase, rounding numbers, or changing data type using astype().
## Commands and Libraries used:    
- pandas (pd) → library used for data manipulation and analysis using DataFrames  
- numpy (np) → library used for numerical operations and handling arrays  
- pd.DataFrame() → create a structured dataset (table) from dictionary, list, or array  
- print() → display dataset or output on screen  
- pd.cut() → perform data binning by dividing continuous data into intervals (bins)  
- bins → define range intervals for grouping values  
- labels → assign category names to each bin  
- df['column'] → access a specific column in DataFrame  
- df['new_column'] = value → create or modify a column  
- df.dtypes → check data types of all columns in dataset  
- astype() → convert data type of a column (e.g., int to float or string)  
- str.upper() → convert text data in a column to uppercase  
- round() → round numerical values to specified decimal places  
- sort_values() → sort dataset based on one or more columns  
- ascending=False → sort in descending order  
- inplace=True → modify original dataset without creating a copy  
- unique() → get unique values from a column  
- value_counts() → count frequency of each category in a column  
- np.nan → represent missing/null values in dataset  
- df.sort_values(by=['column']) → sort dataset using specific column(s)  
- multiple binning → apply pd.cut() on different columns like Price, Units_sold, Delivery_Time, Distance_km  
- categorical columns created → Price_Category, Sales_Category, Order_Category, Delivery_Speed, Delivery_Distance  
- data formatting → process of converting data into suitable format for analysis  
- type conversion chain → df['column'].astype(str).str.upper() → convert to string and format text  
- re-conversion → df['column'].astype(float) → convert back to numeric type after formatting  
- dataset transformation → modifying values, structure, and representation of data for better usability
## Conclusion: 
- Data binning and data formatting are essential preprocessing techniques that improve the quality and usability of data  
- Data binning simplifies complex numerical data by grouping it into meaningful categories, making patterns easier to understand  
- Data formatting ensures consistency by standardizing data types and values, which helps in accurate analysis  
- Together, these techniques make the dataset cleaner, more organized, and ready for effective data analysis and decision-making  

