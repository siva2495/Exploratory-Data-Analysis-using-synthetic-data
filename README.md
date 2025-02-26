# Exploratory-Data-Analysis-using-synthetic-data
##Dataset Overview
The dataset contains 1,000 rows and 9 columns with both numerical and categorical features.
The numerical columns include Area, Bedrooms, Bathrooms, Garage, and Price, while categorical columns include Seller Name, House Location, Pool, and Garden.
Data Quality Investigation
Duplicates: No duplicate entries were found in the dataset.
Missing Values: Several features contained missing values, such as House Location (20), Area (20), Bedrooms (36), Bathrooms (31), Pool (31), Garden (35), Garage (30), and Price (24).
Missing Value Imputation:
Categorical values were filled with mode (most frequent value).
Numerical values were filled with mean.
##Key Data Insights
Average House Price: 376,670.91 INR
Location Distribution:
The dataset includes houses in Trivandrum, Kollam, Ernakulam, Thrissur, and Palakkad.
Trivandrum has the highest number of houses.
##Price Influencing Factors:
Area, number of bedrooms, and number of bathrooms significantly impact house prices.
Presence of a pool (+40,000 INR) and a garden (+15,000 INR) increases the price.
Data Structure:
Object-type columns (categorical): Seller Name, House Location, Pool, Garden.
Float-type columns (numerical): Area, Bedrooms, Bathrooms, Garage, Price.
##Conclusion
The dataset is now cleaned and ready for further analysis.
The primary drivers of price variation are property size, number of rooms, and amenities (pool, garden, garage).
Missing data was handled appropriately, ensuring better model performance in future analyses.
