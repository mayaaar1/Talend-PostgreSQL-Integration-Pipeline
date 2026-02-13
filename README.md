# Talend-PostgreSQL-Integration-Pipeline

📌 Project Overview
This project was completed as part of a practical data management lab. The goal is to implement a complete ETL (Extract, Transform, Load) pipeline for processing structured data.

🛠️ Technologies Used
Talend Open Studio (8.0.1): Creation and mapping of ETL jobs.
PostgreSQL / pgAdmin 4: Database storage and management.
SQL: Schema definition .

⚙️ Pipeline Features
Extraction: Reading .csv and .txt files.
Transformation: Alphabetical sorting (tSortRow) and header insertion.
Loading: Data injection into PostgreSQL and resolution of field capacity errors.

📂 Repository Structure
Tri_fichier_dans_base.zip : Complete archive (Jobs + Metadata).
tp.sql: Script for creating and adjusting the table.
personnes.csv: Data source.
Screenshots: Proof of success (pgAdmin, Excel, Talend).

🚀 How to test the project
Run tp.sql in PostgreSQL.
Import the .zip file into Talend (File > Import > Project Items).
Run the Sort_files_in_database job.
