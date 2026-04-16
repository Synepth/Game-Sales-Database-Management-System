🌍 Language & Naming Convention
Technical Language: Turkish (Database schema, tables, and procedures).

Reason: In accordance with the official academic requirements and instructor specifications for the final exam, the database entities were named in Turkish.

Reviewer Note: Despite the local naming, the architectural logic and optimization strategies follow global industry standards.

🚀 Key Features & Technical Highlights
Relational Schema: 5 core tables (OYUN, MUSTERI, SATIS, YAPIMCI, KATEGORI) interconnected with Primary and Foreign Keys.

Optimization: Implemented a Non-Clustered Index (IND_OyunAdiArama) on game titles to enhance search performance.

Business Logic (Stored Procedures):

SP_KategoriIndirim: Automates bulk discounts for specific game categories.

SP_OyunEkle: Ensures standardized and safe data entry for new titles.

Data Integrity: Used IDENTITY columns, GETDATE() defaults, and CHECK constraints to maintain a clean dataset.

📊 Database Schema (ER Diagram)
The database follows normalization rules to eliminate redundancy. You can view the relationship map in the Images/ folder or via the SSMS Diagram tool.

🛠 Tech Stack
RDBMS: Microsoft SQL Server

Language: T-SQL (Transact-SQL)

Environment: Developed using SSMS (SQL Server Management Studio)

💻 How to Install & Run
Download the GameSalesDB_Script.sql file from this repository.

Open SQL Server Management Studio (SSMS).

Drag and drop the .sql file into SSMS.

Execute the script (F5).

The database OyunSatisDB, all tables, relationships, and sample test data will be created automatically.

📧 Contact

Developed by Arda Köksal LinkedIn | GitHub
