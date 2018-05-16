SELECT * FROM Employee;

SELECT * FROM Employee WHERE City = 'Calgary';
SELECT FirstName, LastName, Max(BirthDate) FROM Employee;
SELECT FirstName, LastName, Min(BirthDate) FROM Employee;
SELECT * FROM Employee WHERE ReportsTo = 2;
SELECT COUNT(*) FROM Employee WHERE City = 'Lethbridge';