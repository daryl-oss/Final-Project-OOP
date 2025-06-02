# Final-Project-OOP
How to run?
-download the project and extract on your file
-open the project in netbeans
-open all classes
-set this database in mysql workbench:
CREATE DATABASE final;
USE final;
CREATE TABLE IF NOT EXISTS tbl (
    id INT AUTO_INCREMENT PRIMARY KEY,
    first_name VARCHAR(50) NOT NULL,
    last_name VARCHAR(50) NOT NULL,
    gender ENUM('Male', 'Female', 'Other'),
    course VARCHAR(100),
    year_level INT
);
then run the class called "main". 
