My Learning Objectives Tracker

Overview
Welcome to the Learning Objectives Tracker project! This repository provides a foundational SQL database schema and data scripts for a personal learning and achievement tracker. It's designed to help you organize and showcase your professional development journey by linking your ongoing and completed learning objectives to a wide range of accomplishments, such as certificates, degrees, licenses, and personal projects.

This project is an excellent way to practice SQL skills, including data modeling, DDL (Data Definition Language) for schema creation, DML (Data Manipulation Language) for data insertion, and complex queries for analysis.

Setup Instructions
Follow these steps to set up the database and populate it with the provided sample data.

Choose a SQL Environment: You will need a database management system to run these scripts. PostgreSQL, MySQL, or SQLite are all great options.

Clone the Repository: Download or clone this repository to your local machine.

Navigate to the SQL Directory: Open your terminal or command prompt and change to the sql/ directory within the project folder.

Create the Database Schema: Run the schema.sql script to create the necessary tables. For example, in a PostgreSQL terminal, you would use:

\i schema.sql

Insert Sample Data: Once the schema is created, run the data.sql script to populate the tables with sample entries.

\i data.sql

Start Querying! The database is now ready for you to practice writing your own queries. Feel free to modify the data or schema to better fit your personal learning goals.

Explanation of Files
The repository is structured to be clear and easy to navigate, with all core project components logically organized.

sql/ Directory
schema.sql: Contains the SQL commands to create the AchievementTypes, Achievements, LearningObjectives, and ObjectiveAchievements tables. This file defines the structure of the database.

data.sql: Contains a series of INSERT statements to populate the tables with example data. This provides a ready-to-use dataset for practicing queries.

docs/ Directory
project_report.md: A detailed project document that serves as a professional portfolio piece. It outlines the problem statement, the database solution, key findings from data analysis, and a project timeline.

presentation_links.md: A markdown file for storing links to any external assets related to the project, such as a presentation deck or a data analysis spreadsheet.

interview_notes.md: A concise, one-page summary of the project, perfect for reviewing key points before an interview.
