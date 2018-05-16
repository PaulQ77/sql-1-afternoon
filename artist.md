INSERT INTO Artist(
  Name)
VALUES
('N.W.A'),
('Vanilla Ice'),
('The Wiggles');
  
SELECT * FROM Artist ORDER BY Name DESC LIMIT 10;
SELECT * FROM Artist ORDER BY Name ASC LIMIT 5;
SELECT * FROM Artist WHERE Name LIKE 'Black%';
SELECT * FROM Artist WHERE Name LIKE '%Black%';