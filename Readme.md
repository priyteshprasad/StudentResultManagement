# Accio Student Result Management System
The project impliments a windows application where two different type of users can log in and perform action accordingly. 
Admin user can register a student, add result to the result table
Student user can view the result.

# Admin:
  Allow uer to
  1. Add Student
  2. Add Student result
  3. Update Student result if already added
  4. View all registered student
  5. View all student result
# Student: 
  Student can put there roll no and then can view their result only if roll no present in result table

# MySQL Tables
1. Result( rollno | physics | maths | em   | dbms | os)
2. Student(rollno | course  | branchName | name     | gender | fathername)

# Tech Stack:
FrontEnd: JSwing help us to create front end components using drag and drop form option palette and set properties 

Backend: Java

DataBase: MySQL,

Dependencies: Project depends upon other projects/libraries
 rs2xml help us to use DbUtils to create tables
 Absolute Layout lets you specify exact locations (x/y coordinates) of its children.


# DataBase Connection
MySQL(RDBMS-Data stored in tabular form). Attribute: table heading, tuple: data rows

Interact with mySql data using JDBC() which connect java with database. MySQLconnector/jlibrary is used to set up the interaction. create connection instance

