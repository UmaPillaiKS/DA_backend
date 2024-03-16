Student Account Management System - Spring Boot Application
This Spring Boot application serves as a platform to manage student data by storing it in a MySQL database. It allows users to input a student's name and contact information, stores it in the database, 
and subsequently fetches and displays this data on another page. The application has been deployed on Azure and can be accessed via the URL: studentaccountda.azurewebsites.net.

Features
Allows users to input a student's name and contact information.
Stores this data in a MySQL database hosted on Azure.
It fetches and displays the stored student data on another page of the application.
Setup
Prerequisites
Java Development Kit (JDK) installed on your machine
MySQL Workbench to interact with the database
Azure account with access to create web apps and databases
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/UmaPillaiKS/StudentManagement.git
cd <project folder>
Update the database connection properties in the application.properties file:
Build the application


Usage
Access the deployed application on studentaccountda.azurewebsites.net.
Use the provided user interface to input student details.
The data will be stored in the MySQL database hosted on Azure.
Navigate to the specified page (e.g., /students) to view the stored student data.

Deployment on Azure
Log in to your Azure portal.
Create an Azure Web App and deploy the built JAR file.
Configure the Azure MySQL database connection settings.
Ensure both the web app and database resources are running.
Access the application using the provided URL.
