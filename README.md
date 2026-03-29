#  Data Cleaning - Global Superstore Dataset

##  Overview
This project focuses on cleaning and preprocessing the Global Superstore dataset using Python and Pandas.  
The objective is to prepare the data for further analysis by handling missing values, duplicates, and formatting issues.


##  Steps Performed
- Extracted dataset from ZIP file
- Loaded Excel file using Pandas
- Explored the dataset using `df.info()` and `df.head()`
- Identified missing values using `df.isnull().sum()`
- Handled missing values using forward fill (`ffill`)
- Removed duplicate records
- Standardized column names (lowercase and trimmed spaces)
- Converted date columns to datetime format


##  Tools Used
- Python 
- Pandas 
- Google Colab 


##  Files in This Repository
- `data_cleaning.ipynb` — Contains the complete data cleaning process  
- `cleaned_superstore.csv` — Final cleaned dataset  


##  Outcome
The dataset was cleaned and prepared for analysis, ensuring:
- No missing values  
- No duplicate records  
- Consistent column formatting  
- Correct data types  


##  What I Learned
- Importance of data cleaning before analysis  
- Handling missing values effectively  
- Removing duplicate data to improve accuracy  
- Working with Pandas for data preprocessing  
- Converting and managing date formats  

