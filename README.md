# CODTECH-SQL-Task4

**Name**: Sahil Ningonda Sankeshwari

**Company**: CODTECH IT SOLUTIONS

**ID** :CT08LPU

**Domain**: SQL

**Tasks Duration**: January 10th,2025 to February 10th, 2025.

**Mentor**: Santhosh

**Task 4: Database Backup and Recovery**

**Objective**:
Demonstrate how to back up and restore a database to safeguard against data loss.

**Purpose**:
Backup and recovery are critical for ensuring data resilience and minimizing downtime during failures.

**Deliverable**:

1.Backup and recovery scripts
2.Documentation describing the steps

**Steps for Task4:**

Step 1: Backup the source_table Using MySQL Workbench

1.Open MySQL Workbench and connect to your database_name database.
2.Click on Server in the top menu and choose Data Export.
3.In the Data Export window:
*Select the internship database from the left-hand panel.
*Check the box for the source_table table.
*Choose Export to Self-Contained File and specify a file name, e.g., source_table_backup.sql.
*Click Start Export.

This will create a sql backup file with the structure and data of the source_table.

Step 2: Simulate Data Loss

Delete all data from source_table.

Output: No rows returned (table is empty)

Step 3: Restore the Data
Restore the table using the backup file.



![Q41](https://github.com/user-attachments/assets/8186e274-977d-41e0-badd-377de0039452)

**Explanation**:

Backup ensures the source_table data is saved in an external file (source_table_backup.sql).
After simulating data loss, the recovery process successfully restored the original data.
