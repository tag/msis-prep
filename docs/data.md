---
authors:
  - Tom Gregory
date: 2020-09-28
---

# Data Modeling & SQL

You should be familiar with the core concepts of relational databases like data modeling, normalization, and SQL.

## During the MSIS Program

As part of the MSIS program you will design data-driven applications, and pull data from databases for statistical modeling. You will also learn about application architectures, and the trade-offs between structured and unstructured data, and between relational and non-relational data stores. Lastly, you will be introduced to databases from several vendors.

<!-- ## Data Modeling -->

## Major Concepts

Before entering the MSIS program, you should be able to do the following:
1. Build a correct relational data model and express it as an ER or logical diagram.
2. Explain the difference between _**data**_, information, and knowledge.
3. Explain the difference between _**structured**_ and _**unstructured**_ data.
4. _**Normalize**_ a data model using at least First Normal Form thru Third Normal Form, and BCNF.
5. Model your data using ERD and logical diagrams

*[BCNF]: Boyce-Codd Normal Form
*[ERD]: Entity–Relationship Diagram
*[RDMS]: Relational Database Management System (aka DBMS, Database Management System)

## Normalization

1. The following two tutorials will introduce you to data Normalization:
    * ["Normalization in DBMS: 1NF, 2NF, 3NF and BCNF with Examples"](https://hackr.io/blog/dbms-normalization), by Aman Goel
    * ["Normalization in DBMS: 1NF, 2NF, 3NF and BCNF in Database"](https://beginnersbook.com/2015/05/normalization-in-dbms/), by Chaitanya Singh


<!-- TODO:
### Practice
 -->

## SQL
1. You should be familiar with how to use SQL to insert, update, and retrieve data from a database. You should also be able to create and drop tables.
<!-- Include these ideas somewhere -->
*[DML]:Data Manipulation Language
*[DDL]:Data Definition Language
2. It would be to your advantage to have experience installing and using a RDMS such as MySQL, MS SQL Server, or SQLite (pick one). This will also allow you to do the practice problems below.
3. Probably the easiest (free) way to learn SQL is via the ["Intro to SQL" unit][khan-sql] in Khan Academy's "Computer Programming" course.

[khan-sql]:(https://www.khanacademy.org/computing/computer-programming/sql)
4. Two good—but very different—books on SQL include:

    * _Sams Teach Yourself SQL in 10 Minutes a Day (5th Edition)_, Ben Forta, Sams Publishing (2019), ISBN-13: 978-0135182796, [[Amazon]](https://www.amazon.com/gp/product/0135182794/) Highly recommended. This book covers SQL as understood by MySQL, SQLite, MS SQL Server, and several other RDMS.
    * _Head First SQL: Your Brain on SQL_, Lynn Beighley, O'Reilly Media (2007), ISBN-13: 978-0596526849 [[Amazon]](https://www.amazon.com/Head-First-SQL-Brain-Learners/dp/0596526849/). The "Head First" series of books are quirky, fun, and easy to read. Readers either love or hate the style (most love it). This book focuses primarily on SQL as used by the MySQL database engine.

5. Installing software:

    * It's best if you get the practice installing, setting up, and using your own database, but free resources exist as well. [DB Fiddle](https://www.db-fiddle.com) and [SQL Playground](https://sql-playground.wizardzines.com) both provide ways to practice SQL via your web browser, without installing any software.

    * If you wish to install a database on your local machine (yes!), we recommend [MySQL](https://dev.mysql.com/doc/mysql-installation-excerpt/5.7/en/) or [SQLite](https://www.sqlite.org/download.html) (use the pre-compiled bundles with command line tools).

## Practice
1. Rick Watson has published an ["Classic Models" database and SQL file][watson-sql] (assumes MySQL), along with a set of practice problems, to accompany his book[^watson-book] on data modeling and SQL. You should be able to successfully write queries for his [sample problems][watson-sql] in these categories:
    * "Single Entity" (all)
    * "One to many relationship" (all)
    * "Many to many relationship" (all)
    * "General queries", simple aggregations, such as problems #7, and #20–#24.

2. Those with an advanced knowledge of SQL (not required, but encouraged) will also be able to complete all of the problems in the "General Queries" and "Correlated subqueries" categories.

[watson-sql]:https://www.richardtwatson.com/dm6e/Reader/ClassicModels.html#
[^watson-book]:Rick Watson is author of _Data Management: Databases and Organizaitons (sixth edition)_ (2020) [[Amazon]](http://www.amazon.com/dp/B00E8HS8N2).
