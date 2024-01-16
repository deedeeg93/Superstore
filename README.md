# Superstore
Here I am checking the basics of a superstore.

SELECT * FROM superstore;
SELECT item_name FROM superstore WHERE price ='39.99';
SELECT AVG(price) FROM superstore;
SELECT MAX(price) FROM superstore;
SELECT MIN(price) FROM superstore;
SELECT AVG(price) FROM superstore WHERE category='Appliances';
SELECT item_name FROM superstore WHERE price>'20';
SELECT item_name FROM superstore WHERE stock_quantity<'30';
SELECT MIN(average_rating) FROM superstore WHERE average_rating>'4.5';
SELECT item_name FROM superstore WHERE average_rating>'4.6';
SELECT SUM(price) FROM superstore;
SELECT item_name FROM superstore WHERE price>'100';
SELECT item_name FROM superstore WHERE category=('Kitchen Supplies' AND price>'50');
SELECT category FROM superstore WHERE stock_quantity<'30';
SELECT price FROM superstore WHERE stock_quantity>'200';
