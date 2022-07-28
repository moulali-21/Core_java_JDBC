# Core_java_JDBC

The project implements a programmed solution to compute average assignment rating and overall rating for each student and/or subjects to measure effectiveness of learning.

There are multiple subjects and each subject has its own assignment categories - test, lab, project and quiz. Each student can give similar assignment different times. So each time when similar assignment category is entered for a student for a similar subject, the program automatically calculates the assignment number and appends at the end of the name of the category (For eg. test_1, test_2, test_3 and so on).

App.java file contains main method. To run the program execute App.java file.


# To exectute the code successfully.
MySQL database is used in this project. Its dependecy is written into the pom.xml file. If you want to use another database, provide relevant dependency in pom.xml file, and respective driver class, url, username and password for database in JDBCConnection.java file.

Table Queries.txt contains the SQL queries to create database with different required tables.

App.java file contains main method. To run the program execute App.java file.
