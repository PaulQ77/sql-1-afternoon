SELECT COUNT(*) FROM Invoice WHERE BillingCountry = 'USA';
SELECT Max(Total) FROM Invoice;
SELECT Min(Total) FROM Invoice;
SELECT * FROM Invoice WHERE Total > 5;
SELECT COUNT(*) FROM Invoice WHERE Total < 5;
SELECT COUNT(*) FROM Invoice WHERE BillingState IN ('CA', 'TX', 'AZ');
SELECT AVG(Total) From Invoice;
SELECT SUM(Total) From Invoice;