# 🚀Exploratory Data Analysis Bootcamp Session Report:
Had an exciting hands on session to conduct an in-depth Exploratory Data 
Analysis on different datasets, uncovering insights, patterns, and 
relationships within the data. Through this analysis, gained familiarity 
with various EDA techniques and derived meaningful conclusions from the 
datasets.

In this session we explored 2 Test Cases:
# 📌Test Case 1 (EDA1) : 
Food delivery service Dataset (service based) : The goal is to better 
understand service usage, performance metrics, and customer behaviour.
# 📌Test Case 2 (EDA2) :                    
Product Dataset (product based)

# 🗃️Datasets Used :
# EDA1 : 
1. 'zwigato.csv' : having information about restaurants, cuisines,
   type of delivery, ratings etc 
3. 'Country-Code.xlsx' : for mapping of country codes to country names.

# ✅Main Steps :
1. Importing important libraries like numpy, pandas, matplotlib,
   seaborn etc
2. Importing the data i.e. 'zwigato.csv' and 'Country-Code.xlsx'
3. Cleaning the data from duplicates, NULL values and  making sure
   data is in correct datatypes
4. Data Visualization:
   
   i) Univariate Analysis :
   
     -> Based on Statistical data, checked for skewness, outliers etc.
   
     -> Pie charts for top countries and cities
   
     -> Count plots for rating colors, delivery options, and city
        categories

   ii) Bivariate Analysis : Clustered bar plots for aggregate ratings
       by country
   
5. Insights & Observations :
   
   -> There are outliers in right tail for 'Average Cost for two'
      and 'Votes' columns.
 
   -> There are outliers in left tail for 'Aggregate Rating' column.
 
   -> India dominates in restaurant count and online delivery.

   -> India is the major contributor to 0 ratings, and the other
      countries’ contributions are negligible.

# 🚩Challenges Faced:
   1) Encoding issues : resolved using 'latin-1' during CSV import
      
   2) Missing values in 'Cuisines' column : since the proportion of
      missing data was small, removed the rows with missing values

# 📊Visualizations Included
   -> Pie charts (Top countries, cities, online delivery)

   -> Count plots (Rating color, city category)
   
   -> Clustered bar plots (Aggregate rating by country)

# 👥 Collaborators

   Special thanks to:

   • Chirag Jhumkawala
   • Pranav Jaipurkar	
   • Sandhya Hinduja
   • Shivani Tripathi

   for their guidance, support and contributions.
  

   
   
