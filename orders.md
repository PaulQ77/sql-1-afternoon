DROP TABLE IF EXISTS orders;

CREATE TABLE orders(
  personID INTEGER,
  productName STRING,
  productPrice DECIMAL,
  quantity INTEGER
  );
  
INSERT INTO orders
(personID, productName, productPrice, quantity)
VALUES
(1, 'golf balls', 12, 2),
(2, 'tennis balls', 8, 4),
(2, 'footballs', 9, 1),
(3, 'baseballs', 2, 7),
(3, 'basketballs', 4, 2);
  
SELECT * FROM orders;
SELECT SUM(quantity) FROM orders;
SELECT SUM(productPrice) FROM orders;
SELECT SUM(productPrice * quantity) FROM orders WHERE personID = 3; 
 
