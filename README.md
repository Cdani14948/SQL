SELECT *
FROM superstore
LIMIT 5;

SELECT item_name, price
FROM superstore
ORDER BY price;

SELECT MAX(price)
FROM superstore;

SELECT price, item_name
FROM superstore
WHERE category="Kitchen Supplies";

-- Welcome to my SQL portfolio! This code repository contains examples of SQL I've written. Feel free to take a look and reach out if you have any questions.
