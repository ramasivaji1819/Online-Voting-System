# Online-Voting-System

# Overview

An Online Voting System built using JSP. This project aims to automate the voting process, allowing multiple parties to be added, and the system automatically determines the winner based on maximum votes.

# Abstract

The main objective of this web-based application is to reduce the time at voting booths while ensuring secure and anonymous voting.

# Key features of the system include:

A login page for users to enter the voting portal.

Display of different parties with their symbols.

Option to vote for a preferred party anonymously.

Submission of votes with voter information and total votes stored securely in a database.

Implementation of MVC (Model-View-Controller) design pattern for better structure and maintenance.

The front-end uses HTML, CSS, and Bootstrap, while MySQL is used for database management. The project runs on Apache Tomcat Server.

# Technologies Required

Java

JSP & Servlets

HTML, CSS, Bootstrap

MySQL

Apache Tomcat Server

# Features

Secure Login System: Only registered users can access the voting portal.

Anonymous Voting: Users can vote without revealing their choice.

Vote Tracking: Each vote is stored in the database, ensuring accurate results.

Result Display: Automatically calculates and displays the winning party.

MVC Architecture: Separates application logic, presentation, and database handling.

# Setup Instructions

1.Install required software:

Java JDK

Apache Tomcat Server

MySQL Database

2.Database Setup:

Create a database named VotingDB.

Import the SQL script provided to create necessary tables (users, votes, parties).

3.Deploy the Project:

Place the project folder in the webapps directory of Tomcat.

Start Tomcat server and open the application via http://localhost:8080/YourProjectName.

4.Access the Application:

Register a voter account or use preloaded test accounts.

Vote for the preferred party and check results.

# Project Structure
OnlineVotingSystem/
│
├── WebContent/               # Frontend files (HTML, JSP, CSS, Images)
│   ├── index.jsp             # Login page
│   ├── vote.jsp              # Voting page
│   ├── results.jsp           # Display voting results
│   ├── register.jsp          # Voter registration page (optional)
│   ├── css/                  # CSS files for styling
│   │   └── style.css
│   └── images/               # Party symbols and other images
│       └── party1.png
│
├── WEB-INF/                  # Configuration and library files
│   ├── web.xml               # Deployment descriptor
│   └── lib/                  # JDBC driver (e.g., mysql-connector-java.jar)
│
├── SQL/                      # Database scripts
│   └── VotingDB.sql          # Script to create tables and insert sample data
│
└── README.md                 # Project documentation

# Contributors

Butta Rama Sivaji – Initial Development

Dakka Rajesh – UI & Frontend Development
