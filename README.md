# Exploratory-Data-Analysis-using-synthetic-data


## Dataset Overview
- The dataset contains 1,000 rows and 9 columns with both numerical and categorical features.

- The numerical columns include Area, Bedrooms, Bathrooms, Garage, and Price, while categorical columns include Seller Name, House Location, Pool, and Garden.

## Data Quality Investigation
- Duplicates: No duplicate entries were found in the dataset.

- Missing Values: Several features contained missing values, such as House Location (20), Area (20), Bedrooms (36), Bathrooms (31), Pool (31), Garden (35), Garage (30), and Price (24).

## Missing Value Imputation:
- Categorical values were filled with mode (most frequent value).

- Numerical values were filled with mean.

## Key Data Insights
- Average House Price: 376,670.91 INR

- Location Distribution:

- The dataset includes houses in Trivandrum, Kollam, Ernakulam, Thrissur, and Palakkad.

- Trivandrum has the highest number of houses.

## Price Influencing Factors:
- Area, number of bedrooms, and number of bathrooms significantly impact house prices.

- Presence of a pool (+40,000 INR) and a garden (+15,000 INR) increases the price.

## Data Structure:
- Object-type columns (categorical): Seller Name, House Location, Pool, Garden.

- Float-type columns (numerical): Area, Bedrooms, Bathrooms, Garage, Price.

## Conclusion
- The dataset is now cleaned and ready for further analysis.

- The primary drivers of price variation are property size, number of rooms, and amenities (pool, garden, garage).

- Missing data was handled appropriately, ensuring better model performance in future analyses.

## Learnings
- Data Generation and Simulation
  - Using Faker, random, and numpy to generate synthetic datasets for analysis.
  - Understanding how to create realistic datasets for testing and modeling.
  - Introducing controlled randomness for simulating real-world scenarios.
- Data Exploration & Summarization
  - Using data.shape, data.dtypes, and data.describe() to understand the dataset structure.
  - Differentiating between numerical and categorical features.
  - Identifying unique values in each feature.
- Data Visualization for EDA
  - Creating bar charts to visualize unique values in categorical and numerical features.
  - Using missingno library to analyze missing values visually.
  - Applying matplotlib for graphical representation of missing data locations.
- Data Quality Assessment
  - Detecting duplicate records in the dataset using duplicated().
  - Checking for missing values using isnull().sum().
  - Understanding how missing values impact dataset quality and analysis
- Handling Missing Values
  - Using mode imputation for categorical features (e.g., fillna(mode())).
  - Using mean imputation for numerical features (fillna(mean())).
  - Understanding when and why to use different imputation techniques.
- Feature Engineering & Price Calculation
  - Using the apply function to create a new feature (Price).
  - Understanding how different property attributes (e.g., area, bedrooms, pool) impact pricing.
  - Introducing random noise (np.random.normal) to simulate real-world pricing variations.
- Statistical Analysis & Insights Extraction
  - Calculating average house prices from the dataset.
  - Analyzing house distribution across locations.
  - Understanding how to pose questions and extract business insights from data.
