<!-- # SQL Fundamentals for Beginners

Welcome to the SQL Fundamentals for Beginners, a complete hands-on interactive experience to learn the basics of SQL, focusing on the practical and different flavors of SQL.

This site is curated for the SQL Fundamentals for Beginnners sharing session. It contains several references that I find useful across over the internet, and would love to share it with other learners. While it is not an exhaustive list, this is a repository with high-yield links sites that will help beginners in learning SQL. 

As of August 2024, I have added several changes to the workshop, including:
- include additional SQL flavors such as [DuckDB](https://duckdb.org/), [PostgreSQL](https://www.postgresql.org/), [MySQL](https://www.mysql.com/), [SQLite](https://www.sqlite.org/), and [MongoDB](https://www.mongodb.com/) (this is NoSQL)
- include additional Graphical User Interface (GUI) tools such as pgAdmin, SQL Server Management Studio (SSMS), MongoDB Compass, [DBeaver](https://dbeaver.io/download/), and SQLiteStudio

The following are the popular databases based on SQL flavors:
- SQL Server T-SQL: [AdventureWorks](https://github.com/Microsoft/sql-server-samples/releases/download/adventureworks/AdventureWorks-oltp-install-script.zip)
- PostgreSQL: [DVDrental](https://www.postgresqltutorial.com/wp-content/uploads/2019/05/dvdrental.zip)
- MySQL: [Sakila](https://downloads.mysql.com/docs/sakila-db.tar.gz)
- DuckDB: [DuckDB](https://motherduck.com/docs/getting-started/sample-data-queries/attach-sample-database/)
- SQLite: [Chinook](https://www.sqlitetutorial.net/wp-content/uploads/2018/03/chinook.zip)
- MongoDB: [Sample Dataset](https://www.mongodb.com/docs/atlas/sample-datasets/current/sample-datasets-sakila/)

## Motivation to share

I have been using SQL for over 3 years, and I still learn something new every day. I remember for every new concept and tools, I need to spend hours to understand the concept and how it works across different SQL flavors. I love to share my knowledge with others, and I hope you find this repository helpful.

**Prerequisites** 
- Ensure your personal laptop is ready for the workshop, download the files and the scripts for hands-on exercises with one of the following methods:
- Clone the workshop repo with **git clone** https://github.com/Syarmine/SQL-Masterclass.git. 
-  Using this method, the scripts will be under folders by module inside sqlworkshops-sql2022workshop\sql2022workshop. You can download git for windows from https://gitforwindows.org or using Github for Dekstop.
- or download the files and scripts one by one from this page. You will need to expand the zip file after downloading.
- A virtual machine or computer running Windows 10, Windows 11, with at least 4 CPUs and 8Gb RAM. You will need Administrator rights on the virtual machine or computer. It is recommended to use your own personal laptop, **do not** use company laptop or owned by others.


🎯 What'll you get from this session:
* Learn how to install SQL Server Management Studio and SQL Server
   * Install SQL Server 2022: https://go.microsoft.com/fwlink/p/?linkid=2215158&clcid=0x4409&culture=en-my&country=my
      * Choose basic installation
    * Install SQL Server Management Studio: https://aka.ms/ssmsfullsetup
      * [Connecting to your database engine](https://learn.microsoft.com/en-us/sql/relational-databases/lesson-1-connecting-to-the-database-engine?view=sql-server-ver16) 
    * Tools: SQL Server Management Studio, SQL Server 2022, Excel, PowerBI (optional)
    * PC Requirement: https://learn.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-ver16
    * Video installation instruction: 
        * Install SQL Server 2022 and SSMS 20: https://www.youtube.com/watch?v=25r0w86YPwY
        * Connect to SQL Server using SSMS: https://www.youtube.com/watch?v=FB7vfufL4gE
* How to create a table: learning the logic - things are more similar than they are different (Excel, PowerBI, SQL)
    * Create a table using Excel
    * Create a table using PowerBI
    * [Create a table using SQL Server](https://learn.microsoft.com/en-us/sql/t-sql/lesson-1-creating-database-objects?view=sql-server-ver16)
* Understanding scripts for database creation and administration
    * Download [popular databases](https://github.com/microsoft/sql-server-samples/tree/master/samples/databases) used in most MOOCs/courses - Adventureworks, Contosso, Northwind and Wide World Importers
    * Download [AdventureWorks-oltp-install-script.zip](https://github.com/Microsoft/sql-server-samples/releases/download/adventureworks/AdventureWorks-oltp-install-script.zip) and extract the zip file to your folder (i.e: C:\Samples\AdventureWorks) folder.
* Connect SQL Server to Excel and PowerBI 
    * Connect your SQL Server data to Excel and PowerBI
    * Basic SQL Query
* Expand learning curve using MOOCs and Github for learning
    * Documentation:
        * [SQL Server Management Studio Documentation](https://learn.microsoft.com/en-us/sql/sql-server/?view=sql-server-ver16)
        * [Microsoft SQL Documentation](https://learn.microsoft.com/en-us/sql/?view=sql-server-ver16)
        * [Educational SQL Resources](https://learn.microsoft.com/en-us/sql/sql-server/educational-sql-resources?view=sql-server-ver16)
        * [Microsoft Tutorial](https://learn.microsoft.com/en-us/sql/ssms/quickstarts/ssms-connect-query-sql-server?view=sql-server-ver16)
    * Query Cheatsheet:
        - [SQL Basic Cheatsheet (Datacamp)](https://images.datacamp.com/image/upload/v1675360372/Marketing/Blog/SQL_Basics_For_Data_Science.pdf)
        - [SQL Quick Access (W3 Schools)](https://www.w3schools.com/sql/sql_quickref.asp)
        - [SQL Cheatsheet Basic and Intermediate (Dataquest)](https://www.dataquest.io/wp-content/uploads/2021/01/dataquest-sql-cheat-sheet.pdf)
        - [A collection of SQL Cheatsheet (Github)](https://github.com/FranzDiebold/data-science-cheat-sheets)
    * Free high quality MOOC for SQL learning
        - [Database design course (8 hours) - (freecodecamp)](https://www.youtube.com/watch?v=ztHopE5Wnpc) **MUST WATCH !!** 
        - [Full SQL Tutorial - MySQL (4 hours) - (freecodecamp)](https://youtu.be/HXV3zeQKqGY?si=4gXicfg2YeEbCnS0) 
        - [SQL Server Performance Essential - SQL Server (4 hours) - (freecodecamp)](https://youtu.be/HvxmF0FUwrM?si=h_5fTBZZkav1Oyft)
        - [SQL Tutorial for beginners - MySQL (5 hours) - (freecodecamp)](https://www.youtube.com/watch?v=-fW2X7fh7Yg)
        - [Google Data Analytics Certificate - Process Data from Dirty to Clean](https://www.coursera.org/learn/process-data?specialization=google-data-analytics)
    * Certifications (optional)
        - [Microsoft Azure Data Fundamentals](https://learn.microsoft.com/en-us/credentials/certifications/azure-data-fundamentals/?practice-assessment-type=certification)
        - [Microsoft Azure Database Administrator Associate](https://learn.microsoft.com/en-us/credentials/certifications/azure-database-administrator-associate/?practice-assessment-type=certification)
        - [Google Data Analytics Certificate - Process Data from Dirty to Clean](https://www.coursera.org/learn/process-data?specialization=google-data-analytics)
        - [Oracle Database Certification](https://academy.oracle.com/en/solutions-curriculum-database.html)

    * Practice Your SQL
        + W3 Schools: https://w3schools.com/sql/default.asp
        + SQLZoo: 
        https://sqlzoo.net/wiki/SQL_Tutorial
        + SQLBolt: 
        https://sqlbolt.com
        + Stratascratch: 
        https://platform.stratascratch.com/coding?code_type=5
        + Leetcode: https://leetcode.com/studyplan/top-sql-50/ (need sign in)

## Repository Stats
![GitHub language count](https://img.shields.io/github/languages/count/Syarmine/intro-predictive-accounting-analytics)
![GitHub top language](https://img.shields.io/github/languages/top/Syarmine/intro-predictive-accounting-analytics)
![GitHub repo size](https://img.shields.io/github/repo-size/Syarmine/intro-predictive-accounting-analytics)
![GitHub last commit](https://img.shields.io/github/last-commit/Syarmine/intro-predictive-accounting-analytics) -->
