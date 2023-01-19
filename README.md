# Hospital_management_system_using_tkinter_GUI_python
Python Tkinter is used for creating an GUI based application that can perform CRUD operation over application.

First create database in SQL. (related queires are provided below)


create database hospital_management;

use hospital_management;

create table appointments (
id int auto_increment primary key,
name varchar(50), 
age int, 
gender varchar(10), 
location varchar(200), 
phone bigint
);

INSERT INTO appointments ( name, age, gender, location, phone) VALUES('SAM', '23', 'Male', '211 Wolf Street', '9999999999');

create table doctors (
id int auto_increment primary key,
name varchar(50),
age int, 
speciality varchar(100), 
gender varchar(10), 
avalability varchar(30), 
phone bigint
);

INSERT INTO doctors ( name,age, speciality, gender, avalability, phone) VALUES('Dr. Krish', '45', 'Heart Specialist', 'Male', 'Yes', '9879876565');

then go to the hospital_management.py file and change the connections of the database as per your requirements.

after than Run the code in terminal:
python3 hospital_management.py

