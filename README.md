# Home_Sales

In this challenge, you'll use your knowledge of SparkSQL to determine key metrics about home sales data. Then you'll use Spark to create temporary views, partition the data, cache and uncache a temporary table, and verify that the table has been uncached.


Answer the following questions using SparkSQL:

What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.

Year -  AvgPrice

2019 - $300,263.70

2020 - $298,353.78

2021 - $301,819.44

2022 - $296,363.88

What is the average price of a home for each year it was built that has three bedrooms and three bathrooms? Round off your answer to two decimal places.

date_built - avg_price

2010 - $292,859.62

2011 - $291,117.47

2012 - $293,683.19

2013 - $295,962.27

2014 - $290,852.27

2015 - $288,770.30

2016 - $290,555.07

2017 - $292,676.79

What is the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.

date_built - avg_price

2010 - $285,010.22

2011 - $276,553.81

2012 - $307,539.97

2013 - $303,676.79

2014 - $298,264.72

2015 - $297,609.97

2016 - $293,965.10

2017 - $280,317.58

What is the "view" rating for homes costing more than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.

rating - avg_price

0 - $403,848.51

1 - $401,044.25

10- $401, 868.43

100-$1,026,669.50

11- $399,548.12
