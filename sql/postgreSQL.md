## postgreSQL

### programming aspects
 
 1. [Chapter 8.Data Types][datatypes]
 2. [Arrays][arrays]
 3. [character type][1]
 4. [Composite Types][compositetypes]
 4. [how to import csv file data into a postgresql table][3]
 5. [SQL: Use a calculated fields from the SELECT in the WHERE clause][12]
 6. [Category (factorial type from `R`) column in SQL][14]
 7. [Count of `true` values][15]
 8. [Representing Sparse Data in PostgreSQL][representing_sparse_data]
 
#### String

 1. [SQL Server CONCAT() Function][9]

#### Date And Time

 1. [Postgresql Interval, Date, Timestamp and Time Data Types][7]
 2. [postgresql official doc - 9.9. Date/Time Functions and Operators][13]
 3. [postgresql convert interval to readable hour minutes and seconds format][8]
 4. [How do I convert an interval into a number of hours with postgres?][10]
 5. [PostgreSQL EXTRACT Function][11]

#### Index

 1. [11.9. Index-Only Scans and Covering Indexes](https://www.postgresql.org/docs/11/indexes-index-only-scans.html)

### Management

 1. [Run a PostgreSQL .sql file using command line arguments][4]
 2. [How to manage PostgreSQL databases and users from the command line][16]
    
    NOTE that you need to specify `psql -d postgres` on login, otherwise it will prompt `database $username not found`.
    
 3. [How do I login and authenticate to Postgresql after a fresh install?][2]
 4. [Calling the psql command without selecting any database][5]
 5. [Import table dump (.sql) using pgAdmin][6]
 6. [Difference Between Schema and Database]

### Extensions
 1. [pgcrypto for hashing user password](https://www.postgresql.org/docs/8.3/pgcrypto.html)
 2. [How to use fuzzy string matching with Postgresql](https://www.freecodecamp.org/news/fuzzy-string-matching-with-postgresql/)

[1]: https://www.postgresql.org/docs/9.1/datatype-character.html
[2]: https://stackoverflow.com/questions/2172569/how-do-i-login-and-authenticate-to-postgresql-after-a-fresh-install
[3]: https://stackoverflow.com/questions/2987433/how-to-import-csv-file-data-into-a-postgresql-table
[4]: https://stackoverflow.com/questions/9736085/run-a-postgresql-sql-file-using-command-line-arguments
[5]: https://superuser.com/questions/655399/calling-the-psql-command-without-selecting-any-database
[6]: https://stackoverflow.com/a/55519761
[7]: https://www.2ndquadrant.com/en/blog/know-what-time-it-is/
[8]: https://stackoverflow.com/questions/41412802/postgresql-query-for-hour-minutes-and-seconds
[9]: https://www.w3schools.com/sql/func_sqlserver_concat.asp
[10]: https://stackoverflow.com/questions/952493/how-do-i-convert-an-interval-into-a-number-of-hours-with-postgres
[11]: https://www.postgresqltutorial.com/postgresql-extract/
[12]: https://stackoverflow.com/questions/8896829/sql-use-a-calculated-fields-from-the-select-in-the-where-clause
[13]: https://www.postgresql.org/docs/current/functions-datetime.html#FUNCTIONS-DATETIME-EXTRACT
[14]: https://stackoverflow.com/questions/9599127/category-column-in-sql
[15]: https://stackoverflow.com/a/5397655/8375400
[16]: https://www.a2hosting.com/kb/developer-corner/postgresql/managing-postgresql-databases-and-users-from-the-command-line#Creating-PostgreSQL-users?aid=1656214

[datatypes]: https://www.postgresql.org/docs/9.5/datatype.html
[arrays]: https://www.postgresql.org/docs/9.5/arrays.html
[compositetypes]: https://www.postgresql.org/docs/9.5/rowtypes.html
[representing_sparse_data]: https://stackoverflow.com/questions/2593250/representing-sparse-data-in-postgresql
[Difference Between Schema and Database]: https://techdifferences.com/difference-between-schema-and-database.html
