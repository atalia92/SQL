# SQL
SQL Portfolio

Project #1: Superstore Analysis

#Display all items by price:

SELECT *
FROM superstore
GROUP BY price;


#What is the average price of items in the category column?

SELECT AVG(price), category
FROM superstore;


#What is the sum of the category Kitchen Supplies?

SELECT SUM(price)
FROM superstore 
WHERE category= "Kitchen Supplies";


#How many Cozy Throw Blankets are in stock?

SELECT stock_quantity
FROM superstore
WHERE item_name= "Cozy Throw Blanket";
