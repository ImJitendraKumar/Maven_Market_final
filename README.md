# Maven_Market_final
Maven_market_final_project
completed the following steps and Done project


1) Connected to the MavenMarket_Customers csv file
Added a new column named "full_name" to merge the the "first_name" and "last_name" columns, separated by a space
Created a new column named "birth_year" to extract the year from the "birthdate" column, and format as text
Created a conditional column named "has_children" which equals "N" if "total_children" = 0, otherwise "Y"

2) Connected to the MavenMarket_Products csv file
Replaced "null" values with zeros in both the "recyclable" and "low-fat" columns

3) Connected to the MavenMarket_Stores csv file
Added a calculated column named "full_address", by merging "store_city", "store_state", and "store_country", separated by a comma and space (hint: use a custom separator)
Added a calculated column named "area_code", by extracting the characters before the dash ("-") in the "store_phone" field 
4) Connected to the MavenMarket_Regions csv file
5) Connected to the MavenMarket_Calendar csv file
Used the date tools in the query editor to add the following columns:
Start of Week (starting Sunday
Name of Day
Start of Month
Name of Month
Quarter of Year
Year
6) Connect to the MavenMarket_Returns csv file

7) Added a new folder on My desktop (or in your documents) named "MavenMarket Transactions", containing both the MavenMarket_Transactions_1997 and MavenMarket_Transactions_1998 csv files
Connected to the folder path

8)  In the MODEL view, arranged tables with the lookup tables above the data tables
Connected Transaction_Data to Customers, Products, and Stores using valid primary/foreign keys 
Connected Transaction_Data to Calendar using both date fields, with an inactive "stock_date" relationship
Connected Return_Data to Products, Calendar, and Stores using valid primary/foreign keys
Connected Stores to Regions as a "snowflake" schema

9) NOW required DAX measures have been added.
10) Building the Report 
