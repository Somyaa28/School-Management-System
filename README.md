# School Management System

## Introduction
The School Management System is a comprehensive application designed to streamline administrative tasks and manage student records efficiently. It provides a user-friendly interface for adding, viewing, and deleting student information, ensuring smooth operations within educational institutions.

## Features
- *Student Records*: Allows administrators to maintain detailed records of students, including their names, contact information, gender, date of birth, and stream.
- *Add Record*: Enables the addition of new student records to the database, ensuring all relevant information is captured accurately.
- *Delete Record*: Provides functionality to remove student records from the database, helping to keep the records up to date.
- *View Record*: Allows users to view specific student records for reference or verification purposes.
- *Reset Fields*: Offers the option to clear all input fields, facilitating ease of use and reducing data entry errors.
- *Data Persistence*: Utilizes a SQLite database to store student records, ensuring data integrity and seamless retrieval.

## Requirements
- Python 3.x
- Tkinter (usually included with Python installation)
- tkcalendar library (install via pip install tkcalendar)

## Usage
1. Launch the application to access the main window.
2. Use the left frame to input student information, including name, contact number, email address, gender, date of birth, and stream.
3. Click on the "Submit and Add Record" button to add the student record to the database.
4. Use the center frame to perform additional actions such as deleting records, viewing records, or resetting input fields.
5. The right frame displays a Treeview widget containing a list of student records, which can be scrolled through and selected for viewing or deletion.

## Database Management
- The application uses a SQLite database named SchoolManagement.db to store student records.
- The database schema includes a table named SCHOOL_MANAGEMENT with columns for student ID, name, email, phone number, gender, date of birth, and stream.

## Conclusion

The School Management System represents a significant advancement in streamlining administrative tasks and managing student records within educational institutions. By providing a user-friendly interface and robust functionality, the system offers administrators a powerful tool to maintain accurate and up-to-date student information efficiently.

Throughout the development of this project, key features such as adding, viewing, and deleting student records were implemented using Python and Tkinter, along with the integration of a SQLite database for data storage. This ensures data integrity and facilitates seamless retrieval of student information.

