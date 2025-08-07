# SQL-Task-3
#Hospital Database 

# Goal of this Task

To learn how to get data from one or more tables using SQL queries like:

SELECT

WHERE

ORDER BY

LIMIT



---

#Tools Used

MySQL Workbench

(You can also use DB Browser for SQLite)



---

#About the Database

This project uses a Hospital database with 3 tables:

1. Patients

Stores information about patients.

Columns: patient_id, name, age, gender, admission_date


2. Doctors

Stores information about doctors.

Columns: doctor_id, name, speciality, experience_years


3. Appointments

Stores information about doctor-patient appointments.

Columns: appointment_id, patient_id, doctor_id, appointment_date, status



---

#What You Will Learn

You will learn how to:

Select all or specific columns from a table

Filter data using WHERE, AND, OR

Use LIKE to search for patterns

Use BETWEEN for date or number ranges

Sort results using ORDER BY

Limit the number of results using LIMIT

Use AS to rename columns

Use DISTINCT to remove duplicates



---

# Examples of SQL Queries

-- Show all patients
SELECT * FROM Patients;

-- Show patients older than 40
SELECT * FROM Patients WHERE age > 40;

-- Show doctors with more than 10 years of experience
SELECT * FROM Doctors WHERE experience_years > 10;

-- Show appointments from latest to earliest
SELECT * FROM Appointments ORDER BY appointment_date DESC;

-- Show only the first 3 appointments
SELECT * FROM Appointments LIMIT 3;

-- Show patient names and ages with different column names
SELECT name AS PatientName, age AS Age FROM Patients;

-- Show all unique genders from patients table
SELECT DISTINCT gender FROM Patients;


---

#Files Included

hospital_task3.sql → Contains:

Code to create database and tables

Sample data

SELECT queries



---

#What You'll Get Out of This Task

You’ll understand how to get data from a database using different types of SELECT queries.

You'll be more confident in filtering, sorting, and formatting results.



---

Let me know if you'd like this in .txt, .md, or .pdf format!
