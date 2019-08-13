Examples of DBMS (Database Management System)

- Oracle
- MySQL
- Postgres
- MS SQL Server
- SQLite**
- MongoDB (NoSQL: Document)

DB Objects
- Tables: Is where the data is stored.
- Views
- Indexes
- Store Procedures
- Functions

Schema === Structure

"select * from customers"
-Selects all columns from the table customers

"select customerName, city, country from customers"
-Selects the columns CustomerName, City, and Country from the Customers Table.

"select country, city, customerName from customers where city = 'London'

"select country, city, customerName from customers where city = 'London or country = 'USA'

"Select * from [Products] where price > 10 order by productName, supplierId desc"(descending order, it defaults to ascending)

"Select country, city, * FROM [Customers] order by country, city"

"Select * from [products] order by price desc limit 5 offset 5"

"Insert into products (productName, supplierId, categoryId, unit, price) values ('iRubberBand', 3, 2, 'one unit', 10)"

"Delete from products" (Deletes everything in products)

"select * from products where supplierId = 12"

"delete from products where supplierId = 12"

"update products set categoryId = 4, price = 25 where supplierId = 11" (update and set allows you to update)

[client] <> [api] <SQL> (driver) <> [dbms]

npm i knex sqlite3