# IBM-Databases-and-SQL-for-DS-with-Python
A hands on Assignment, you will be working on a real world dataset provided by the Chicago Data Portal. Imagine, you have been hired by a non-profit organization that strives to improve educational outcomes for children and youth in the City of Chicago. Your job is to analyze the census, crime, and school data for a given neighborhood or district. You will identify causes that impact the enrollment, safety, health, environment ratings of schools.

Instructions:

1. Review the datasets

Before you begin, you will need to become familiar with the datasets. Snapshots for the three datasets in .CSV format can be downloaded from the following links:

    Chicago Socioeconomic Indicators: Click here

    Chicago Public Schools: Click here

    Chicago Crime Data: Click here

NOTE: Ensure you have downloaded the datasets using the links above instead of directly from the Chicago Data Portal. The versions linked here are subsets of the original datasets and have some of the column names modified to be more database friendly which will make it easier to complete this assignment. The CSV file provided above for the Chicago Crime Data is a very small subset of the full dataset available from the Chicago Data Portal. The original dataset is over 1.55GB in size and contains over 6.5 million rows. For the purposes of this assignment you will use a much smaller sample with only about 500 rows.

2. Load the datasets into a database
Perform this step using the LOAD tool in the Db2 console. You will need to create 3 tables in the database, one for each dataset, named as follows, and then load the respective .CSV file into the table:

    CENSUS_DATA

    CHICAGO_PUBLIC_SCHOOLS

    CHICAGO_CRIME_DATA

To load the data into the tables the steps are similar to Week 2 Lab 1 Part II. The only difference with that lab is that in Step 5 of the instructions you will need to click on create (+) New Table and specify the name of the table you want to create and then click Next.

image

3. Write and execute queries

Problem 1: Find the total number of crimes recorded in the CRIME table.
Problem 2: List community areas with per capita income less than 11000.
Problem 3: List all case numbers for crimes involving minors?
Problem 4: List all kidnapping crimes involving a child?(children are not considered minors for the purposes of crime analysis)
Problem 5: What kind of crimes were recorded at schools?
Problem 6: List the average safety score for all types of schools.
Problem 7: List 5 community areas with highest % of households below poverty line.
Problem 8: Which community area(number) is most crime prone?
Problem 9: Use a sub-query to find the name of the community area with highest hardship index.
Problem 10: Use a sub-query to determine the Community Area Name with most number of crimes?
