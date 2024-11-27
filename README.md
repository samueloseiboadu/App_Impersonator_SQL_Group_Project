# Project: App Impersonator – Pharmacy Database Simulation
This project emulates the functionality of an app that stores and manages user data, such as a pharmacy application handling prescription records. 
It showcases how an app can interact with a SQL database to store, update, and delete information, providing insight into foundational database management practices.

## Project Overview
The goal of this project is to demonstrate SQL skills by imagining how a real-world application would manage data using a database. 
The chosen scenario involves a pharmacy application that stores prescription details. Key functionalities include creating the database, inserting sample records, updating data to reflect changes, and deleting records to simulate data management processes.

## Key Features
### Database Creation:

A database named G3_pharmacyDB is created to store prescription records.

### Table Definition:

A table, Prescriptions, is designed with the following schema:
prescription_id (Primary Key)
- client_name
- medication_name
- dosage
- prescription_date
- refill_date

### Sample Data Insertion:

The Prescriptions table is populated with 50 sample records, reflecting real-world scenarios such as prescriptions for different clients and medications.

### Update Operations:

An SQL UPDATE statement is used to modify the dosage for a specific prescription, showcasing how apps handle edits in their stored data.

### Delete Operations:

An SQL DELETE statement demonstrates the removal of a record, simulating the deletion of a prescription entry in the app.

### Querying Data:

SQL SELECT statements are employed to view and verify changes to the data, ensuring that operations are executed correctly.

### Why This Project?
This project highlights practical SQL operations that are critical in app development and database management:

- Designing efficient table structures.
- Managing data lifecycles through insertion, updates, and deletions.
- Ensuring data integrity and accuracy through query execution.

### SQL Code Highlights
Here are some key SQL statements used in the project:

- Table Creation:

CREATE TABLE Prescriptions(
    prescription_id INT PRIMARY KEY,
    client_name TEXT,
    medication_name TEXT,
    dosage TEXT,
    prescription_date DATE,
    refill_date DATE
);

- Data Insertion:

INSERT INTO Prescriptions VALUES (1, 'Abokomah', 'Lisinopril', '10 mg', '2024-10-01', '2024-11-01');

- Updating a Record:

UPDATE Prescriptions
SET dosage = '15 mg'
WHERE prescription_id = 44;

- Deleting a Record:

DELETE FROM Prescriptions
WHERE prescription_id = 44;

## Skills Demonstrated
SQL database creation and schema design.
Data manipulation using INSERT, UPDATE, and DELETE.
Querying and verifying data changes.

This project serves as a solid foundation for database management concepts and is a practical demonstration of how apps interact with SQL databases in the real world.
