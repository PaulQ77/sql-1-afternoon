DROP TABLE IF EXISTS person;

CREATE TABLE person (
  id INTEGER PRIMARY KEY AUTOINCREMENT,
  name STRING,
  age INTEGER,
  height INTEGER,
  city STRING,
  favoriteColor STRING
  );
  
INSERT INTO person (
  name, 
  age, 
  height,
  city,
  favoriteColor
  )
  
  VALUES
  ('Bobby Bones', 21, 182, 'Dallas', 'Black'),
  ('Bonesy Bob', 18, 123, 'Phoenix', 'Red'),
  ('Phil Lip', 34, 178, 'Tucson', 'Green'),
  ('Judy Blue', 43, 200, 'New York', 'Orange'),
  ('Harry Sally', 27, 134, 'Tuscaloosa', 'Blue');
  
  SELECT * FROM person ORDER BY height DESC;
  SELECT * FROM person ORDER BY height ASC;
  SELECT * FROM person ORDER BY age DESC;
  SELECT * FROM person WHERE age > 20;
  SELECT * FROM person WHERE age = 18;
  SELECT * FROM person WHERE age < 20 OR age > 30;
  SELECT * FROM person WHERE age != 27;
  SELECT * FROM person WHERE favoriteColor != 'Red';
  SELECT * FROM person WHERE favoriteColor != 'Red' AND favoriteColor != 'Blue';
  SELECT * FROM person WHERE favoriteColor = 'Orange' OR favoriteColor = 'Green';
  SELECT * FROM person WHERE favoriteColor IN ('Orange', 'Green', 'Blue');
  SELECT * FROM person WHERE favoriteColor IN ('Yellow', 'Purple');
