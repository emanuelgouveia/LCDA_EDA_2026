# Public Datasets for Exploratory Data Analysis

This document contains links to various public datasets suitable for learning exploratory data analysis techniques.

---

## 1. Non-Clean Datasets (with missing values, duplicates, NaNs)

These datasets contain data quality issues such as missing values, duplicates, and NaNs that require preprocessing.

1. **Titanic Dataset**
   - Link: https://www.kaggle.com/datasets/brendan45774/test-file
   - Description: Famous dataset with passenger information from the Titanic. Contains missing values in Age, Cabin, and Embarked columns.

2. **House Prices Dataset**
   - Link: https://www.kaggle.com/datasets/c/house-prices-advanced-regression-techniques
   - Description: Residential home data from Ames, Iowa. Contains numerous missing values across multiple features.

3. **Melbourne Housing Market**
   - Link: https://www.kaggle.com/datasets/anthonypino/melbourne-housing-market
   - Description: Housing data with missing values and potential duplicates that need cleaning.

4. **WHO Life Expectancy**
   - Link: https://www.kaggle.com/datasets/kumarajarshi/life-expectancy-who
   - Description: Health and economic data with many missing values for various countries.

5. **Air Quality UCI**
   - Link: https://archive.ics.uci.edu/dataset/360/air+quality
   - Description: Air quality sensor data with -200 values representing missing data and sensor failures.

---

## 2. Datasets with Multiple Tables for Joining

These datasets contain at least 2 tables that can be joined using common keys.

1. **Northwind Database**
   - Link: https://github.com/microsoft/sql-server-samples/tree/master/samples/databases/northwind-pubs
   - Description: Classic database with multiple tables (Orders, Customers, Products, etc.) that can be joined.

2. **Sakila DVD Rental Database**
   - Link: https://dev.mysql.com/doc/sakila/en/
   - Description: Sample database with 16 tables including Film, Actor, Customer, Rental that can be joined.

3. **AdventureWorks Dataset**
   - Link: https://github.com/Microsoft/sql-server-samples/releases/tag/adventureworks
   - Description: Comprehensive database with multiple related tables for sales, products, and customers.

4. **IMDb Non-Commercial Datasets**
   - Link: https://developer.imdb.com/non-commercial-datasets/
   - Description: Multiple tables (movies, ratings, crew, principals) that can be joined via movie IDs.

5. **Stack Overflow Data**
   - Link: https://www.kaggle.com/datasets/stackoverflow/stackoverflow
   - Description: Multiple tables including Users, Posts, Comments, Votes that can be joined.

---

## 3. Multivariate Datasets with Mixed Variable Types

These datasets contain multiple variables with different types (numeric, categorical, boolean, etc.).

1. **Adult Income Dataset (Census)**
   - Link: https://archive.ics.uci.edu/dataset/2/adult
   - Description: Mix of continuous and categorical variables predicting income levels.

2. **Bank Marketing Dataset**
   - Link: https://archive.ics.uci.edu/dataset/222/bank+marketing
   - Description: Banking campaign data with numeric, categorical, and boolean variables.

3. **Wine Quality Dataset**
   - Link: https://archive.ics.uci.edu/dataset/186/wine+quality
   - Description: Physicochemical properties (numeric) and quality ratings (ordinal) of wines.

4. **Automobile Dataset**
   - Link: https://archive.ics.uci.edu/dataset/10/automobile
   - Description: Car specifications with mixed types: numeric (price, horsepower), categorical (make, fuel-type).

5. **Student Performance Dataset**
   - Link: https://archive.ics.uci.edu/dataset/320/student+performance
   - Description: Student data with numeric grades and categorical demographic/social variables.

6. **Heart Disease Dataset**
   - Link: https://archive.ics.uci.edu/dataset/45/heart+disease
   - Description: Medical data with continuous, categorical, and binary variables.

7. **Mushroom Classification**
   - Link: https://archive.ics.uci.edu/dataset/73/mushroom
   - Description: All categorical features describing mushroom characteristics.

8. **Credit Card Default**
   - Link: https://archive.ics.uci.edu/dataset/350/default+of+credit+card+clients
   - Description: Mixed numeric (credit limits, payments) and categorical (gender, education) features.

9. **Seattle Pet Licenses**
   - Link: https://www.kaggle.com/datasets/aaronschlegel/seattle-pet-licenses
   - Description: Pet registration data with mixed categorical and date variables.

10. **Employee Attrition Dataset**
    - Link: https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset
    - Description: HR data with numeric (age, salary) and categorical (department, role) variables.

---

## 4. Time Series Datasets

These datasets contain temporal data suitable for time series analysis.

1. **Daily Climate Data**
   - Link: https://www.kaggle.com/datasets/sumanthvrao/daily-climate-time-series-data
   - Description: Daily weather measurements over multiple years.

2. **Stock Market Data (Yahoo Finance)**
   - Link: https://finance.yahoo.com/
   - Description: Historical stock prices with dates (accessible via yfinance Python library).

3. **Electricity Consumption**
   - Link: https://archive.ics.uci.edu/dataset/321/electricityloaddiagrams20112014
   - Description: Time series of electricity consumption from Portuguese clients.

4. **Bitcoin Historical Data**
   - Link: https://www.kaggle.com/datasets/mczielinski/bitcoin-historical-data
   - Description: Minute-by-minute Bitcoin price and volume data.

5. **Air Passengers Dataset**
   - Link: https://www.kaggle.com/datasets/rakannimer/air-passengers
   - Description: Classic time series dataset of monthly airline passenger numbers (1949-1960).

---

## Additional Resources

- **UCI Machine Learning Repository**: https://archive.ics.uci.edu/
- **Kaggle Datasets**: https://www.kaggle.com/datasets
- **Google Dataset Search**: https://datasetsearch.research.google.com/
- **Data.gov**: https://data.gov/
- **European Data Portal**: https://data.europa.eu/

---

## Notes

- Always check the license and terms of use before using any dataset
- Some links may require registration (e.g., Kaggle)
- Datasets are chosen for their educational value and variety of data characteristics
- Consider starting with smaller datasets before moving to larger ones
