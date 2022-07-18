# Walmart_cleaned_Prediction

![1*tgc5PuEaW36qa-60V7_KaA](https://user-images.githubusercontent.com/100385953/179567079-661e37b2-b6f3-47ad-a3a3-dd148cee63a5.jpeg)


Predicting future sales for a company is one of the most important aspects of strategic planning. I wanted to analyze how internal and external factors of one of the biggest companies in the US can affect their Weekly Sales in the future. This module contains complete analysis of data , includes time series analysis , identifies the best performing stores , performs sales prediction with the help of multiple linear regression.
The data collected ranges from 2010 to 2012, where 45 Walmart stores across the country were included in this analysis. It is important to note that we also have external data available like CPI, Unemployment Rate and Fuel Prices in the region of each store which, hopefully, help us to make a more detailed analysis.
[2] Dataset Explanation
I had access to three different data sets from Kaggle.com about the company. These data sets contained information about the stores, departments, temperature, unemployment etc. I will explain each one of the data sets in more detail with each one of its features.
[2.1] Stores:
- Store: The store number. Range from 1–45.
- Type: Three types of stores ‘A’, ‘B’ or ‘C’.
- Size: Sets the size of a Store would be calculated by the no. of products available in the particular store ranging from 34,000 to 210,000.
[2.2] Sales:
-Date: The date of the week where this observation was taken.
-Weekly_Sales: The sales recorded during that Week.
-Store: The store which observation in recorded 1–45.
-Dept: One of 1–99 that shows the department.
-IsHoliday: Boolean value representing a holiday week or not.
[2.3] Features:
Temperature: Temperature of the region during that week.
-Fuel_Price: Fuel Price in that region during that week.
-MarkDown1:5 : Represents the Type of markdown and what quantity was available during that week.
-CPI: Consumer Price Index during that week.
-Unemployment: The unemployment rate during that week in the region of the store.

Data Cleaning and Preprocessing
Data preprocessing is a data mining technique that involves transforming raw data into an understandable format. Real-world data is often incomplete, inconsistent, and/or lacking in certain behaviors or trends, and is likely to contain many errors. Data preprocessing is a proven method of resolving such issues. Data preprocessing prepares raw data for further processing.

Data preprocessing is used database-driven applications such as customer relationship management and rule-based applications (like neural networks). To attain uniformity while analysis the data, we have converted all the Boolean values ( TRUE=1 and FALSE=0) . Most of the time, operators and functions automatically convert a value to the right type. That’s called “type conversion”.
For example, alert automatically converts any value to a string to show it. Mathematical operations convert values to numbers.
There are also cases when we need to explicitly convert a value to put things right.We have replaced all NA values to 0.
