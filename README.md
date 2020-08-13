# SQL Tutorial 
Structured Query Language (SQL) is the standard language to communicate with  relational database management systems. SQL statements are used to perform tasks such as update data on a database, or retrieve data from a database. Some common relational database management systems that use SQL are: Oracle, Sybase, Microsoft SQL Server, Access, Ingres. The standard SQL commands such as "Select", "Insert", "Update", "Delete", "Create", and "Drop" can be used to accomplish almost everything that one needs to do with a database.
## Tables 
A relational database system contains one or more objects called tables. The data or information for the database are stored in these tables. Tables are uniquely identified by their names and are comprised of columns and rows. Columns contain the column name, data type, and any other attributes for the column. Rows contain the records or data for the columns.

## Commands
It is a good practice to run sql commands in upper case. Though sql is not case sensitive 
|Commnad | description |
| -- | --|
| CREATE TABLE "name" (variables) | Creates a new table, if a table with the same name already exists this will generate an error|
| CREATE TABLE IF NOT EXISTS "name"(variables) | This will only create table if it does not exist (Use this instead of CREATE TABLE) |
