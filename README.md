# Zomato_Dataset_Analysis

Most of us know that Zomato is an Indian multinational restaurant aggregator and food delivery company. The idea of analyzing the Zomato dataset is to get an overview of what is actually happening in their business. The Zomato dataset consists of more than 9000 rows with columns such as Restaurant ID, Restaurant Name, City, Location, Cuisines, and many more.

Data Exploration with SQL
Table Details: Checked all the details of the table such as column names, data types, and constraints.
Duplicate Values: Checked for duplicate values in the RestaurantId column.
Unwanted Columns: Removed unwanted columns from the table.
Table Merge: Merged two different tables and added a new column Country_Name with the help of the primary key as the CountryCode column.
Correcting City Names: Identified and corrected the misspelled city names.
Rolling/Movie Count: Counted the number of restaurants by rolling count/moving count using window functions.
Statistics: Checked min, max, average data for votes, rating, and currency columns.
New Category Column: Created a new category column for rating.  

Data Analysis with SQL
After data exploration with SQL, I started working on analyzing the data with SQL where I found the following insights:
1.	Country Distribution: According to this Zomato dataset, 90.67% of data is related to restaurants listed in India followed by the USA (4.45%).
   
2.	Online Delivery: Out of 15 countries, only 2 countries provide online delivery options to their customers:
	28.01% of restaurants in India.
	46.67% of restaurants in the UAE.

3.	Indian Restaurants Insights:
o	Connaught Place in New Delhi has the most listed restaurants (122), followed by Rajouri Garden (99), and Shahdara (87).
o	The most popular cuisine in Connaught Place is North Indian food.
o	Out of 122 restaurants in Connaught Place, only 54 restaurants provide a table booking facility.
o	Average ratings for restaurants with table booking facilities are 3.9/5, compared to restaurants without table booking facilities which are 3.7/5 in Connaught Place, New Delhi.
o	The best moderately priced restaurant with an average cost for two < 1000 INR, rating > 4, votes > 4, and provides both table booking and online delivery options with Indian cuisine is located in Kolkata, India named 'India Restaurant' (RestaurantID - 20747).

