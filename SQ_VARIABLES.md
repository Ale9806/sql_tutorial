 # SQL Data Types
 
 SQL data types can be broadly divided into following categories.

<ol>
  <li>Numeric data types such as int, tinyint, bigint, float, real </li>
  <li>Date and Time data types such as Date, Time, Datetime etc.</li>
  <li>Character and String data types such as char, varchar, text </li>
  <li>Unicode character string data types, for example nchar, nvarchar, ntext</li>
  <li>Binary data types such as binary, varbinary etc.</li>
  <li>Miscellaneous data types – clob, blob, xml, cursor, table </li>
</ol>

<a href="url"><img src="https://cdn.journaldev.com/wp-content/uploads/2017/11/sql-data-types.png" align="left"  width="500"  > </a>

### IMPORTANT:
Not all data types are supported by every relational database vendors. For example, Oracle database doesn’t support DATETIME and MySQL doesn’t support CLOB data type. 
So while designing database schema and writing sql queries, make sure to check if the data types are supported or not.

Data types listed here doesn’t include all the data types, these are the most popularly used data types. Some relational database vendors have their own data types that
might be not listed here. For example, Microsoft SQL Server has money and smallmoney data types but since it’s not supported by other popular database vendors, 
it’s not listed here.

Every relational database vendor has it’s own maximum size limit for different data types, you don’t need to remember the limit.

## Data Types Categories:

### SQL Numeric Data Types:
|Type|From|To|
|--|--|--|
| bit | 0 | 1|
| tinyint | 0 | 255|
| smallint | -32,768 | 32,767|
|int	| -2,147,483,648 | 2,147,483,647 |
|bigint	|-9,223,372,036, 854,775,808| 9,223,372,036, 854,775,807 |
|decimal|-10 <sup> 38 </sup>+1	|10 <sup> 38 </sup> -1 |
|numeric|-10 <sup> 38 </sup>+1	|10 <sup> 38 </sup> -1 |
| float | -1.79E <sup> 308 </sup>|1.79E <sup> 308 </sup>|
|real| -3.40E <sup> 38 </sup>|3.40E <sup> 38 </sup>|

<br>

### SQL Character and String Data Types
|Type | Description |
| -- | -- |
|CHAR|	Fixed length with maximum length of 8,000 characters|
|VARCHAR|	Variable length storage with maximum length of 8,000 characters|
|VARCHAR(max)|	Variable length storage with provided max characters, not supported in MySQL|
|TEXT|	Variable length storage with maximum size of 2GB data|

**Note that all the above data types are for character stream, they should not be used with unicode data.

<br>


### SQL Date and Time Data Types
|Type | Description |
| -- | -- |
|DATE	|Stores date in the format YYYY-MM-DD|
|TIME	|Stores time in the format HH:MI:SS|
|DATETIME	|Stores date and time information in the format YYYY-MM-DD HH:MI:SS|
|TIMESTAMP	|Stores number of seconds passed since the Unix epoch (‘1970-01-01 00:00:00’ UTC)|
|YEAR|	Stores year in 2 digit or 4 digit format. Range 1901 to 2155 in 4-digit format. Range 70 to 69, representing 1970 to 2069.|

<br>


### SQL Miscellaneous Data Types
|Type | Description |
| -- | -- |
|CLOB|	Character large objets that can hold up to 2GB|
|BLOB	|For binary large objects|
|XML	|for storing xml data|
|JSON|	for storing JSON data|

For more information visit [journaldev.](https://www.journaldev.com/16774/sql-data-types])
