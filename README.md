# SpringBoot_Server_WebApi_BackEnd


SETUP
-----
1.Create a Mysql DB = dbtest
sql>CREATE SCHEMA `dbtest` ;
2. Creat a table with name=employees
3. Table structure
     
Fields of employees table
-----------------
id int(11) PK Auto Increment
email_address varchar(255) 
first_name varchar(255) 
last_name varchar(255)

sql>CREATE TABLE `dbtest`.`employees` (
  `id` INT NOT NULL AUTO_INCREMENT,
  `email_address` VARCHAR(45) NULL,
  `first_name` VARCHAR(45) NULL,
  `last_name` VARCHAR(45) NULL,
  PRIMARY KEY (`id`))
COMMENT = '			';

     


RUNNING...
---------
1. Run the Backend site using spring boot, which will run its serivce on 8081 as configured in 
application.properties file

2. Run the Front end angular app, that runs in 4200 port in localhost

3. On front end we must see list of employees, that intally calls the RestApi hosted on server for all CRUD apps
