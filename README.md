<p align="center">
  <img src="logo.png" alt="PlayStore DB" width="150"> </p>

<h1 align="center">PlayStore DB 📈</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Database-PostgreSQL-336791?style=for-the-badge&logo=postgresql" alt="PostgreSQL Badge">
  <img src="https://img.shields.io/badge/Language-SQL-4285F4?style=for-the-badge&logo=mysql" alt="SQL Badge">
  <img src="https://img.shields.io/badge/Normalization-BCNF%2F3NF-FFC107?style=for-the-badge" alt="Normalization Badge">
</p>


# 📱 Playstore DBMS Project

This repository contains the complete database design and implementation of a Playstore-style platform built as part of our **Database Management Systems (DBMS)** course project.

Our project focuses on modeling and managing data for applications, books, developers, users, purchases, and offers—similar to how the Google Playstore operates.

---

## 📚 Contents

| Section                     | Description                                                                 |
|----------------------------|-----------------------------------------------------------------------------|
| 🔸 ER Diagram               | Entity-Relationship Diagram showing the full logical model                  |
| 🔸 Relational Schema        | All relations (tables), primary keys, and foreign keys                      |
| 🔸 Minimal FD Set           | Cleaned set of functional dependencies for all relations                    |
| 🔸 BCNF Proof               | Proof that each relation is in Boyce-Codd Normal Form                       |
| 🔸 SQL DDL Script           | Complete script with `CREATE TABLE`, constraints, and meaningful triggers   |
| 🔸 Triggers                 | Logical triggers ensuring data consistency (like downloads, ratings, etc.) |

---

## 📌 Project Features

- ✅ Well-normalized schema in **BCNF (Boyce-Codd Normal Form)**
- ✅ Includes real-world Playstore entities: apps, users, developers, books, offers, and purchases
- ✅ Implements **data integrity via triggers** and foreign keys
- ✅ Designed for **scalability**, **consistency**, and **clean querying**

---

## 🛠️ Tech Stack

- **SQL** (DDL, Constraints, Triggers)
- **PostgreSQL** using PgAdmin
- **Draw.io / ERD Tool** for diagramming
- **GitHub** for version control and collaboration

---

## 📷 ER Diagram Snapshot

_Refer to `/ER-Diagram/Playstore_ER.png`_

---

## 📝 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/Playstore-DBMS-Project.git
   ```

2. Import the SQL script:
   - Open MySQL Workbench or your DBMS tool
   - Run: `playstore_final_ddl.sql` to create all tables and triggers

3. You’re ready to test and populate!


---

### ⭐ If you like the project, give it a star!
