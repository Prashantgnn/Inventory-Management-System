# Inventory-Management-System

Inventory Management System


This is an Inventory Management System built in the form of a GUI desktop application developed in Java using MySQL as its database. The GUI was designed using Swing and the database connectivity was managed using JDBC API.

This application can be used by any small to mid-sized stores to easily maintain and manage an inventory of all their-

* Products

* Customers

* Suppliers

* Users

* Transactions


Features of the Application

1. Users can manage inventory and stock of all the products available in their store.

2. Users can manage all sales and purchase transactions made by the store.

3.Supports two user types:

- Administrator
- Employee
[Admins have the ability to manage all other personnel.]

4. Any transaction made automatically handles the stock availability in the inventory.

5. Each section includes a search feature to make it easier for users to view the data they want to see.

6. Users only need to enter the product code while making a sale and all the relevant details will be retrieved from the database automatically.

7. Maintains a time log of all the users using the application.

How to download and run the software
Minimum Requirements: JDK or JRE version 16.

1. Download and unzip the ZIP folder: InventoryManagement.zip

2. Download the SQL dump file

3. Import the SQL dump file using MySQL Workbench to locally create the sample schema and tables associated with this software.

4. After the inventory schema has been locally created, you can go ahead and run the JAR file (InventoryManagement.jar) included in the zip folder.

5. Default credentials for the connection to MySQL database is:

- Username: root
- Password: root
Incase your database uses a different username and password to connect, follow these steps:

i) Go to the lib folder in the zip file that you downloaded.
ii) Open the XML source file DBCredentials.xml.
iii) Simply change the values of the two entry tags with values username and password from "root" to whatever username and password you are using. (Ln 12 and 13)
    <properties>
    <comment>Credentials for the database.</comment>
      <entry key="username">root</entry>
      <entry key="password">root</entry>
    </properties>
    
6. Once these credentials match, the JAR file should execute without any issues provided that you have the minimum JRE.

7. You can log into the application using Username: root and Password: root.

Note:
All the project dependencies are available in the lib directory.

