# SQL
**create-databases.sql** will create databases.

### SHOW Databases:
```SHOW DATABASES;```

### Change Database:
Syntax: ``` USE <databaseName>```

```USE sql_store;```

### SHOW Tables:
```SHOW TABLES;```

## Basic Queries:
1. write a query to return all customers

``` SELECT * FROM customers; ```

2. write a query to return all customers but their order should be according to first_name of customers:

``` SELECT * FROM customers ORDER BY first_name; ```

3. write a query to return specific columns from customers table i.e customer first_name, last_name and points

``` SELECT * first_name, last_name, points from customers; ```

4. write a query to add an additional column in the output named as discount calculated as (points + 10) * 100

``` SELECT  last_name, first_name, points, (points + 10) * 100 AS discount_factor FROM customers; ```

5. write a query to duplicate a state name inside customers where customer_id = 1

``` UPDATE customers SET state = 'VA' WHERE (customer_id = 1); ```

6. write a query to not print the one you duplicated in above query i.e print only unique states.

``` SELECT DISTINCT state FROM customers; ```

## Midlevel
--> will add here soon enough.
