Complaint Management System

Objective:
To allow users to submit complaints and check complaint status.

Description:
•	complaint.jsp → user enters complaint issue
•	Servlet → inserts complaint into DB
•	viewStatus.jsp → servlet fetches complaint status and displays to user
•	complaint.jsp + viewStatus.jsp
•	ComplaintServlet
•	JDBC CRUD
•	Response sent back to JSP pages

Database:
CREATE DATABASE complaint_db;
USE complaint_db;

CREATE TABLE complaint (
    id INT AUTO_INCREMENT PRIMARY KEY,
    name VARCHAR(50),
    issue VARCHAR(255),
    status VARCHAR(20)
);





