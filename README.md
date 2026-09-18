# MySQL-PROJECTS
This MySQL project demonstrates database design and SQL query operations using multiple related tables. It covers selection, filtering, sorting, joins, aggregation, subqueries, grouping, HAVING, CASE statements, and practical data analysis queries for calculating averages, counting records, finding top scores, and generating performance reports.

# 🌱 AgriCashew Management System

## 📌 About the Project
The **AgriCashew Management System** is a MySQL-based database project designed to manage and organize information related to **cashew farming and agricultural activities**.
The main purpose of this project is to provide a centralized database where information about **farmers, buyers, farms, harvests, farming equipment, cashew prices, weather conditions, requests, connections, and ratings** can be stored and managed efficiently.
Farmers can maintain their farm and harvest information, while buyers can view farmer-related information and interact with them for business purposes. The system also supports **equipment requests**, allowing users to manage farming equipment and requests.
The project also includes **cashew price management**, which helps store market prices according to quality and date. Weather information can also be maintained to support better farming decisions.
An important part of the system is the **connection between farmers and buyers**. Users can send contact requests and interact with other users. The rating system allows farmers and buyers to provide feedback and build trust with each other.
The database is designed using **Primary Keys and Foreign Keys** to maintain relationships between different tables and avoid unnecessary duplication of data.
SQL queries are used to retrieve and analyze the stored information. The project includes queries using **SELECT, WHERE, ORDER BY, JOIN, GROUP BY, HAVING, aggregate functions, subqueries, CASE statements, and self joins**.
Overall, the AgriCashew Management System provides a structured database solution for managing cashew farming information and improving interaction between **farmers and buyers**.

## 🎯 Objectives
- Manage farmer and buyer information
- Store farm details
- Track cashew harvests
- Manage farming equipment
- Store cashew market prices
- Store weather information
- Allow farmers and buyers to connect
- Manage equipment requests
- Provide ratings and reviews
## 🗄️ Database Name

```sql
agricashew
📋 Database Tables
===================
The project contains the following tables:
Users
Farmers
Buyers
Farms
Harvests
Equipment
Equipment Requests
Contact Requests
Cashew Prices
Weather
Buyer Ratings
Farmer Ratings

🔗 Relationships
====================
The main relationships between the tables are:
Users → Farmers : One-to-One
Users → Buyers : One-to-One
Farmers → Farms : One-to-Many
Farms → Harvests : One-to-Many
Farmers → Equipment : One-to-Many
Equipment → Equipment Requests : One-to-Many
Buyers → Equipment Requests : One-to-Many
Farmers → Buyer Ratings : One-to-Many
Buyers → Farmer Ratings : One-to-Many

🧩 ER Diagram
===============
The ER diagram represents the structure of the AgriCashew database.
Main Entities
==============
Users
Farmers
Buyers
Farms
Harvests
Equipment
Equipment Requests
Contact Requests
Cashew Prices
Weather
Buyer Ratings
Farmer Ratings

ER Diagram Symbols
===================
Rectangle → Entity
Ellipse → Attribute
Diamond → Relationship
PK → Primary Key
FK → Foreign Key
1 : 1 → One-to-One
1 : N → One-to-Many

📊 Main Features
==================
👨‍🌾 Farmer Management
Stores farmer information such as name, contact details, location, and farming experience.
🌾 Farm Management
Stores farm details such as farm name, location, area, and soil type.

🌰 Harvest Management
Stores information about cashew harvests including date, season, quantity, and quality.

🛠️ Equipment Management
Farmers can add and manage farming equipment and buyers can request available equipment.

💰 Cashew Price Management
Stores cashew market prices based on quality, date, and market location.

🌦️ Weather Management
Stores weather information such as temperature, rainfall, humidity, location, and date.

🤝 Farmer and Buyer Connection
Farmers and buyers can send contact requests and communicate with each other.

⭐ Ratings
Farmers and buyers can give ratings and reviews to each other.

🔍 SQL Queries
=================
The project contains SQL queries at Easy, Medium, and Hard levels.
🟢 Easy Queries
Display all farmers.
Find farmers with more than 5 years of experience.
Display Grade A harvests.
Display available equipment.
Find cashew prices greater than 800.
🟡 Medium Queries
Display farmer names and farm names.
Display farmer names with their harvest quantities.
Find the total harvest quantity of each farmer.
Find the average rating of each farmer.
Display equipment details with farmer names.
🔴 Hard Queries
Find the farmer with the highest total harvest.
Find farmers with an average rating greater than 4.
Find farmers who have both Grade A and Grade B harvests.
Calculate the estimated value of a harvest.
Display accepted contact requests between users.

🎯 SQL Concepts Used
This project helps practice:
=============================
SELECT
WHERE
ORDER BY
INNER JOIN
GROUP BY
HAVING
Aggregate Functions
SUM()
AVG()
COUNT()
Subqueries
CASE Statements
Self Join
Primary Keys
Foreign Keys

🛠️ Technologies Used
=======================
MySQL
MySQL Workbench
SQL
Draw.io

🚀 How to Run
===============
Open MySQL Workbench.
Create a new SQL file.
Create the agricashew database.
Select the database.
Create all required tables.
Insert the sample data.
Run the SQL queries.
Use SELECT * to check the data.

** 📁 Project Structure
==========================
AgriCashew-Management-System/
│
├── agricashew.sql
├── AgriCashew ER Diagram.drawio
└── README.md

📌 Conclusion
=================
The AgriCashew Management System is a MySQL-based database project designed to manage important cashew farming information in an organized way. It stores details about farmers, buyers, farms, harvests, equipment, cashew prices, weather conditions, requests, connections, and ratings in separate but related tables.
The project demonstrates the practical use of Primary Keys, Foreign Keys, table relationships, and SQL queries for managing and analyzing data. It includes SQL concepts such as SELECT, WHERE, ORDER BY, JOIN, GROUP BY, HAVING, aggregate functions, subqueries, CASE statements, and self joins.
Overall, AgriCashew provides a structured solution for managing cashew farming activities and improving interaction between farmers and buyers. The project can be further developed into a complete web or mobile application with features such as online cashew sales, notifications, dashboards, farming suggestions, weather-based recommendations, and price prediction.

## 👩‍💻 Author

**Name:** Lavanya Yalamanchi

## 📌 Project Name

**AgriCashew Management System**
