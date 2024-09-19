New! Keyboard shortcuts … Drive keyboard shortcuts have been updated to give you first-letters navigation
# Prediction-of-Products-Sales
A sale prediction for food items sold at various markets.
## Analyzing products & outlets and sale prices for food items for a production company.
Kinda Abuasbeh
### It is essential for a production company to identify which products drive the highest sales and revenues, as well as the most effective outlets that contribute to this success. Additionally, understanding the various factors that can influence total sales is vital for making informed business decisions.
# Data Source 
Big Mart Sales Prediction Problems
https://datahack.analyticsvidhya.com/contest/practice-problem-big-mart-sales-iii/
## Data Dictionary
Variable Name	Description
- Item_Identifier:          	Product ID
- Item_Weight:              	Weight of product
- Item_Fat_Content:          	Whether the product is low-fat or regular
- Item_Visibility:	          The percentage of total display area of all products in a store allocated to the particular product
- Item_Type:	                The category to which the product belongs
- Item_MRP:	                  Maximum Retail Price (list price) of the product
- Outlet_Identifier:	        Store ID
- Outlet_Establishment_Year:	The year in which store was established
- Outlet_Size:	              The size of the store in terms of ground area covered
- Outlet_Location_Type:	      The type of area in which the store is located
- Outlet_Type:	              Whether the outlet is a grocery store or some sort of supermarket
- Item_Outlet_Sales:	        Sales of the product in the particular store. This is the target variable to be predicted.
## To prepare this data, the data was cleaned, and the following processes were performed:

### Exploratory Data Analysis
    - During the exploratory data analysis, a boxplot and histogram was visualized for each numeric datatype column. 
    - Also, a barplot was visualized for each categorical column. 
    - This gave a good baseline for all of the numeric and categorical columns for univariate.

    - Aheat map was visualized for numeric datatype columns, this gave a good view for the whole numerical relations between numeric features.


### Key Points
 - The project's primary objective is to predict food item sales to assist retailers in enhancing their sales strategies.
 - The dataset consists of 8,523 rows and 12 columns, providing a substantial amount of data for analysis.
 - Data cleaning involves exploring the dataset to address issues such as missing values, duplicates, and inconsistent categories.
 - Missing values in the dataset are identified in 'Item_Weight' and 'Outlet_Size' and are replaced with placeholder values.
 - There are no duplicate entries in the dataset, simplifying the data-cleaning process.
 - Inconsistent categories, particularly in 'Item_Fat_Content,' are corrected to ensure uniformity.
 - Summary statistics for numerical columns, such as minimum, maximum, and mean, are generated to provide insights for further analysis.

## Project-Part 4
- we used EDA fundtions to explore our features and plot them against our target ' Item_Outlet_Sales'
- we found out the following:
- ***significant relationships*** between our target and 'Item_MRP', 'Location Type', 'Outlet_Type', 'Outlet_Size' and 'Establishment_Year features.
- ***Moderate Relationships*** between our traget and 'Item_Type', 
- ***Poor Relationships*** between our target and 'Item_Weight', 'Item_Fat_Content
- ***The most interesting fact in the data set was the 'Item_Visibility' feature that's behaving the opposite way than expected, i assumed that sales should rise when visibility rises. However the plot showed Sales declining when Visiblity inclines***
  
