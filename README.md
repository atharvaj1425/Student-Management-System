# student-management-system

This Python code is a student management system using Tkinter for the GUI and MySQL for data storage. It allows the user to:  
1.Add, view, update, or delete student records in a MySQL database.  
2.Collects information such as name, course, subject, contact, and more.  
3.Uses buttons for actions like submitting or viewing records.  
4.Connects to a MySQL database to perform operations such as retrieving, updating, or deleting student data.  
5.Includes custom styling through external modules (custom and credentials).  



****Requirements and Installation****

Use pip3 instead of pip for Linux and Mac.

Install PyMySQL
☛pip install PyMySQL

Install Tkinter
☛pip install tk



****Install MySQL server****



****Create a Database and a Table****

Create a database with this name: "student_management"
☛create database student_management;

Create a table "student_register" under the "student_management" database.  
☛create table student_register(  
	f_name VARCHAR(50) NOT NULL,  
	l_name VARCHAR(50) NOT NULL,  
	course VARCHAR(30) NOT NULL,  
	subject VARCHAR(50) NOT NULL,  
	year Int(10) NOT NULL,  
	age Int(10) NOT NULL,  
	gender char(10) NOT NULL,  
	birth DATE NOT NULL,  
	contact VARCHAR(15) NOT NULL,  
	email VARCHAR(100) NOT NULL,  
	PRIMARY KEY ( contact )  
);


After doing the above steps run the ****main.py**** file.