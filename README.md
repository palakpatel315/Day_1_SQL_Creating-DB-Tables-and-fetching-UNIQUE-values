# Day_1_SQL_Creating-DB-Tables-and-fetching-UNIQUE-values
Creating a Database or Schema following by creating tables in the database and subsequently data import in the tables created in MYSQL.
# Day_1_SQL_Creating DB Tables and fetching UNIQUE values
Creating a Database or Schema followed by creating tables in the database and subsequently importing data into the tables created in MYSQL

## 📅 Challenge: Day 1 List all unique hospital services available in the hospital.

## 📚 Concepts Covered
➡️ Creating Database
➡️ Creating Tables with column names and data types in the created DB
➡️ Table Data Import
➡️ Importance of Commenting and Use of Column Aliases
➡️ Testing with LIMIT while exploring new tables
➡️ Asking the correct questions from the correct tables

## 🏥 Dataset: 
- services_weekly
## columns 
week, month, service, available_beds, patients_request, patients_admitted,	patients_refused,	patient_satisfaction,	staff_morale,	event

## 🧩 Challenge Question

List all unique hospital services available in the hospital.

## ✅ SQL Solution
  ``` MYSQL
  SELECT DISTINCT service AS Hospital_services
  FROM services_weekly;
```
## Result:Hospital_services
- emergency
- surgery
- general_medicine
- ICU

## 💡 Key Learnings
- **DISTINCT** helps fetch unique values from a column.
- Avoid SELECT * in production queries for better performance.

Thank you [Indian Data Club](https://www.linkedin.com/company/indian-data-club/posts/?feedView=all) for starting this challenge and [DPDzero](https://www.linkedin.com/company/dpdzero/) the title sponsor of this challenge

Connect with me on [LinkedIn](https://www.linkedin.com/in/palak-patel-0711242a0/)

[Query and Output Screenshots]()

Data Used [services_weekly](https://github.com/JayaraniArunachalam/Day_1_SQL_Creating-DB-Tables-and-fetch-UNIQUE-values/blob/main/services_weekly.csv)
