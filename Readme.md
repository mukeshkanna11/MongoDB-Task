//Introduction//

MongoDB is a NoSQL document database that uses a flexible, JSON-like format called BSON. It is designed for high performance, high availability, and scalability.

Zen Class Programme - MongoDB README

Table of Contents

//Introduction//

-Database Structure
-Sample Data
-Query Requirements
-MongoDB Queries
-Additional Resources

//Introduction//
This document outlines the MongoDB structure, sample data, and queries required for managing a database for a Zen class programme. The programme includes user information, code challenges, attendance records, topics covered, tasks assigned, company drives, and mentors.

//Database Structure//
(Collections)
users - Contains user information such as name, role (e.g., student, mentor), and other relevant details.
codekata - Tracks problems solved by users in code challenges.
attendance - Records attendance status (present/absent) for users on specific dates.
topics - Stores information about topics covered in classes, including the date taught.
tasks - Stores tasks assigned to users, including submission status.
company_drives - Details of company placement drives, including participating users.
mentors - Contains information about mentors, including mentee counts and IDs.
