# Smart-Event-waste-Management-System
This project demonstrates practical use of MySQL database design, relationships, CRUD operations, joins, filtering, aggregation, grouping, and data analysis for a real-world event sustainability and waste-management scenario.

# Smart Event Resource & Waste Lifecycle Management System

## 📌 Project Description

The **Smart Event Resource & Waste Lifecycle Management System** is a MySQL database project developed to manage the complete resource and waste lifecycle of different events. The system maintains structured information about event organizers, venues, events, resources, staff, tasks, waste generation, waste segregation, waste collection, and recovery activities.

The main objective of this project is to provide a centralized database for tracking **event resources and waste from allocation and usage to collection, segregation, recycling, reuse, and recovery**. The database uses primary keys and foreign-key relationships to connect different entities and maintain organized data.

## 🗂️ Main Modules

* **Event Organizers** – Stores organizer and contact information.
* **Venues** – Maintains venue details, capacity, location, and waste facility availability.
* **Events** – Stores event type, date, attendance, organizer, venue, and event status.
* **Resource Management** – Manages reusable and non-reusable resources and their availability.
* **Resource Allocation** – Tracks resources allocated, used, damaged, and returned for events.
* **Staff & Volunteers** – Maintains people involved in event operations and their roles.
* **Event Tasks** – Assigns and tracks tasks performed by staff and volunteers.
* **Waste Categories** – Classifies waste such as food waste, plastic, paper, glass, metal, and e-waste.
* **Waste Records** – Records the quantity and source of waste generated during events.
* **Waste Segregation** – Tracks recyclable, compostable, reusable, and non-recyclable waste.
* **Waste Collection** – Maintains collection details and waste destinations.
* **Recovery Partners** – Stores recycling, composting, reuse, and recovery organizations.
* **Recovery Records** – Tracks recovered materials and quantities processed by recovery partners.

## 📊 SQL Concepts Covered

This project provides practical implementation of:

* Database and table creation
* Primary Keys and Foreign Keys
* Constraints and relationships
* Data insertion
* Data retrieval using `SELECT`
* Filtering using `WHERE`
* Sorting using `ORDER BY`
* Grouping using `GROUP BY`
* Aggregate functions
* Table joins
* Subqueries
* Data analysis and reporting
* Data verification

## 🔄 Project Workflow

**Event Planning → Resource Allocation → Event Execution → Resource Usage → Waste Generation → Waste Segregation → Waste Collection → Recycling/Composting/Reuse → Material Recovery**

This workflow helps track resources and waste throughout the event lifecycle instead of managing event waste as a single final-stage activity.

## 🎯 Project Objective

The project aims to demonstrate how a relational database can be used to organize and analyze event-related resource usage and waste-management activities. It provides a structured approach to monitoring waste quantities, segregation, collection, and recovery while also maintaining event, resource, and staff information.

## 🛠️ Technologies Used

* **Database:** MySQL
* **Language:** SQL
* **Concept:** Relational Database Management System (RDBMS)

## 📁 Project Structure

```text
Smart-Event-Resource-Waste-Management/
│
├── smart_event_waste_management.sql
└── README.md
```

## 🚀 Key Learning Outcome

Through this project, I practiced designing a **real-world relational database**, creating interconnected tables, maintaining relationships using foreign keys, inserting structured data, and writing SQL queries for managing and analyzing event resource and waste information.

-----------------------------------
Queries
---------
Basic Level

Topics used in our project:

SELECT statement
Selecting specific columns
SELECT *
WHERE clause
Filtering records
Comparison operators
=
>
<
>=
<=
Boolean conditions
ORDER BY
ASC / DESC sorting
LIMIT
COUNT()
SUM()
Column aliases using AS
Basic data retrieval

--------------------
Intermediate Level
-------------------
Topics used in our project:

GROUP BY
Aggregate functions with GROUP BY
COUNT() with GROUP BY
SUM() with GROUP BY
HAVING clause
GROUP BY + ORDER BY
INNER JOIN
Joining multiple tables
Table aliases
Combining JOIN with aggregate functions
Multiple-table data analysis
Grouping data based on categories
Filtering grouped results using HAVING

-------------------------------
Hard / Advanced Level
----------------------
Topics used in our project:

Subqueries
Multiple subqueries in one SELECT
Subqueries with aggregate functions
Nested calculations
ROUND() function
COALESCE() function
Percentage calculation
Complex JOIN + GROUP BY + ORDER BY + LIMIT
Multi-table aggregation
Sustainability report generation
Dashboard-style SQL queries
Combining multiple independent calculations into one result
Overall project statistics
Advanced data analysis using aggregated results
