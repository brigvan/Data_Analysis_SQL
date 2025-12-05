# Data Analysis SQL

This is a collection of some real-world projects available on DataCamp that can be carried out using PostgreSql.


## 1 Analyze International Debt Statistics
**Description**: In this project, you are going to analyze international debt data collected by The World Bank.

**Dataset**:The dataset contains information about the amount of debt (in USD) owed by developing countries across several categories. 

**Questions to answer** 
1. What is the number of distinct countries present in the database?
2. What country has the highest amount of debt?
3. What country has the lowest amount of repayments?

## 2 Analyzing Motorcycles Part Sales
**Description**: You're working for a company that sells motorcycle parts, and they've asked for some help in analyzing their sales data!
They operate three warehouses in the area, selling both retail and wholesale. They offer a variety of parts and accept credit cards, cash, and bank transfer as payment methods. However, each payment type incurs a different fee.
The board of directors wants to gain a better understanding of wholesale revenue by product line, and how this varies month-to-month and across warehouses. 

**Dataset**:The database, which contains a table called *sales*, consisting of columns such as the type of product ordered, the amount, the price per product, payment method, date of the order, etc. 

**Questions to answer** 
1. You have been tasked with calculating net revenue for each product line and grouping results by month and warehouse. The results should be filtered so that only "Wholesale" orders are included, for the months of June, July and August


## 3 Analyzing Students' Mental Health
**Description**: A Japanese international university surveyed its students in 2018 and published a study the following year that was approved by several ethical and regulatory boards.
The study found that international students have a higher risk of mental health difficulties than the general population, and that social connectedness (belonging to a social group) and acculturative stress (stress associated with joining a new culture) are predictive of depression. Explore the students data using PostgreSQL to find out if you would come to a similar conclusion for international students and see if the length of stay is a contributing factor.

**Dataset**:The database, which contains a table called *sales*, consisting of columns such as the type of product ordered, the amount, the price per product, payment method, date of the order, etc. 

**Questions to answer** 
1. Explore and analyze the students data to see how the length of stay (stay) impacts the average mental health diagnostic scores of the international students present in the study.


## 4 Analyzing Unicorn Companies
**Description**: You have been asked to support an investment firm by analyzing trends in high-growth companies. They are interested in understanding which industries are producing the highest valuations and the rate at which new high-value companies are emerging. Providing them with this information gives them a competitive insight as to industry trends and how they should structure their portfolio looking forward.

**Dataset**:The database consists of 4 tables:
1. *Dates*: contains information about the date a company was founded and the year it became a unicorn
2. *Funding*: for every company, it contains information about the company value in US dollars,the amount of funding raised in US dollars, a list of key investors in the company
3. *Industries*: for every company, it describes the industry that the company operates in.
4. *Company*:  for every company id, it displays the name of the company well as the city/country/continent where the company is headquartered.
   
**Questions to answer** 
1. First identify the three best-performing industries based on the number of new unicorns created in 2019, 2020, and 2021 combined.
2. From those industries (1), you will need to find the number of unicorns within these industries (2), the year that they became a unicorn (3), and their average valuation, converted to billions of dollars and rounded to two decimal places (4).


## 5 Analyzing and formatting PostgreSQL Sales Data



**Description**: In this project, you will work with data from a hypothetical Super Store to challenge and enhance your SQL skills in data cleaning. This project will engage you in identifying top categories based on the highest profit margins and detecting missing values, utilizing your comprehensive knowledge of SQL concepts.

**Dataset**:The database consists of 4 tables: *orders* (info about each order), *returned orders* (info on whether a order was retuened or not), *people* (name of the Salesperson accredited with the order and the region they operate in), *products* (info about the products ordered)

**Questions to answer** 
1. Find the top 5 products from each category based on highest total sales.
2. Calculate the quantity for orders with missing values in the quantity column


## 6 Exploring Trends in American Baby Names
**Description**: How have American baby name tastes changed since 1920? Which names have remained popular for over 100 years, and how do those names compare to more recent top baby names? These are considerations for many new parents, but the skills you'll practice while answering these queries are broadly applicable.

**Dataset**:You'll be working with data provided by the United States Social Security Administration, which lists first names along with the number and sex of babies they were given to in each year. For processing speed purposes, the dataset is limited to first names which were given to over 5,000 American babies in a given year. The data spans 101 years, from 1920 through 2020.

**Questions to answer** 
1. List the first five names in alphabetical order and find out if each name is "Classic" or "Trendy.
2. What were the top 20 male names overall, and how did the name Paul rank?
3. Which female names appeared in both 1920 and 2020?
