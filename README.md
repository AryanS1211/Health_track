# Health_track
SQL-based Health & Fitness Analytics project using Oracle Database

📊 Health Track: Personal Health & Fitness Analytics Project
A beginner-friendly SQL project that analyzes daily health and fitness data using Oracle Database 21c. This project is designed to strengthen SQL skills while working with realistic health tracking data, including steps, calories, sleep, and water intake.

📌 Objective
To create a health analytics system using SQL that helps monitor user fitness trends and generate insights using real-time queries and window functions.

🛠️ Tools & Technologies
Database: Oracle Database 21c Express Edition

Language: SQL (Oracle SQL syntax)

Platform: Oracle SQL Developer

📁 Project Structure
Health_track_SQL_Project/
│
├── SQL_Files/
│   ├── create_tables.sql
│   ├── insert_data.sql
│   ├── analysis_queries.sql
│
├── Documentation/
│   └── README.md  

👥 Dataset Description
Custom data for 20 users, including:

Personal details (name, gender, age, height, weight)

Daily activity logs (steps, sleep, workout minutes, water intake)

Meal logs (calories, protein, carbs, fat, etc.)

📊 Key Features
✅ Created and linked normalized tables using foreign keys
✅ Inserted realistic dummy data for 20 users
✅ Performed health and fitness analytics using:

JOIN, GROUP BY, HAVING

Aggregate Functions (SUM, AVG, MAX, MIN)

Window Functions (ROW_NUMBER, RANK, AVG OVER)

Subqueries and filters

Weekly trends and leaderboards

Water and calorie tracking

🔍 Sample Analysis Queries
Top 5 active users in the last 7 days

Users who consumed more than 2000 calories per day

Moving average of water intake (window function)

Weekly step count leaderboard

Sleep duration vs. workout correlation check

Join-based summaries per user

All queries are tested and written specifically for Oracle SQL.

📈 Example Insight
"Aryan Sawant had the highest average steps in the last 7 days, while Deepa More maintained the most consistent water intake."

📎 How to Run the Project
Set up Oracle Database 21c XE

Open Oracle SQL Developer

Run create_tables.sql

Run insert_data.sql
