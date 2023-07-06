# Inventory-Management-System

Inventory Management System
This is an Inventory Management System built in the form of a GUI desktop application developed in Java using MySQL as its database. The GUI was designed using Swing and the database connectivity was managed using JDBC API.

This application can be used by any small to mid-sized stores to easily maintain and manage an inventory of all their-

Products
Customers
Suppliers
Users
Transactions
Features of the Application
Users can manage inventory and stock of all the products available in their store.

Users can manage all sales and purchase transactions made by the store.

Supports two user types:

Administrator
Employee
[Admins have the ability to manage all other personnel.]

Any transaction made automatically handles the stock availability in the inventory.

Each section includes a search feature to make it easier for users to view the data they want to see.

Users only need to enter the product code while making a sale and all the relevant details will be retrieved from the database automatically.

Maintains a time log of all the users using the application.

How to download and run the software
Minimum Requirements: JDK or JRE version 16.
Download and unzip the ZIP folder: InventoryManagement.zip

Download the SQL dump file

Import the SQL dump file using MySQL Workbench to locally create the sample schema and tables associated with this software.

After the inventory schema has been locally created, you can go ahead and run the JAR file (InventoryManagement.jar) included in the zip folder.

Default credentials for the connection to MySQL database is:

Username: root
Password: root
Incase your database uses a different username and password to connect, follow these steps:

Go to the lib folder in the zip file that you downloaded.
Open the XML source file DBCredentials.xml.
Simply change the values of the two entry tags with values username and password from "root" to whatever username and password you are using. (Ln 12 and 13)
  <properties>
  <comment>Credentials for the database.</comment>
    <entry key="username">root</entry>
    <entry key="password">root</entry>
  </properties>
Once these credentials match, the JAR file should execute without any issues provided that you have the minimum JRE.

You can log into the application using Username: root and Password: root.

Note:
All the project dependencies are available in the lib directory.

