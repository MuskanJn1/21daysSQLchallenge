# 21 Days SQL Challenge 💪

Welcome to my 21 Days SQL Challenge!  
Each day focuses on learning and practicing a specific SQL concept with examples and exercises.

---

## 📅 Day 1: The SELECT Statement
*Focus:* Learning how to retrieve data from a database using SELECT.

### Key Concepts Covered
- Tables store data in rows (records) and columns (fields)
- SELECT helps you choose which columns to retrieve
- FROM specifies the table you're querying
- Always end SQL statements with a semicolon (;)

💡 **What I Learned:**
- How to view and filter data using SELECT
- How to choose specific columns for cleaner queries
- How to inspect table structure
- How to find unique values using DISTINCT

- 📸 I’ve attached queries for reference.
### Practice Questions:
--Retrieve all columns from the `patients` table.
 -> 
 select * from patients

--Select only the `patient_id`, `name`, and `age` columns from the `patients` table.
 -> select patient_id,name,age from patients

--Display the first 10 records from the `services_weekly` table.
-> select top(10)* from services_weekly

### Day1 Challenge:
--List all unique hospital services available in the hospital.
 -> select distinct(service) from services_weekly

⚠️ **Pro Tips to Remember:**
- Avoid using SELECT * in production — it's inefficient and may return unnecessary data
- Use **column aliases** to improve readability, especially in complex queries

- ---

## 🧠 How to Use This Repo
1. Clone this repository:
   ```bash 
   https://github.com/MuskanJn1/21daysSQLchallenge.git
