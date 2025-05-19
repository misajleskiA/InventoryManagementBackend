# 📦 Inventory Management Backend

This is the backend service for an Inventory Management system built with **Spring Boot**, using **PostgreSQL** for data persistence and **Maven** for project management.

---

## 🛠️ Backend Setup Guide (Spring Boot)

### ✅ Requirements

Make sure you have the following installed:

- **Java Development Kit (JDK) 17 or higher**
- **Maven**
- **PostgreSQL**
- **IntelliJ IDEA** (or any preferred IDE like Eclipse)

If you're not sure how to install any of these, Google them individually or refer to the official installation pages:

- [Java 17 (Oracle)](https://www.oracle.com/java/technologies/javase/jdk17-archive-downloads.html)
- [Maven](https://maven.apache.org/install.html)
- [PostgreSQL](https://www.postgresql.org/download/)

---

## 🗄️ Database Configuration (PostgreSQL)

1. **Start PostgreSQL** on your machine.
2. **Create the database** using the terminal or pgAdmin:

   ```sql
   CREATE DATABASE inventory_management_db;
3.	**Note** your PostgreSQL credentials (username and password) — you'll use them in the next step.

   ---
## 📁 Project Setup & Run
1.**Open the project** in IntelliJ IDEA (or your preferred IDE).

2.**Navigate to:** src/main/resources/application.properties

3.**Update these lines** with your PostgreSQL credentials:
   
**spring.datasource.url=jdbc:postgresql://localhost:5432/inventory_management_db**

**spring.datasource.username=YOUR_USERNAME**

**spring.datasource.password=YOUR_PASSWORD**

   ---
 ## ▶️ Running the App  
 1.In IntelliJ IDEA, open this file:
    
**src/main/java/com/yourpackage/InventoryManagementBackendApplication.java**

2.Right-click on the file and select Run (Or click the green ▶️ icon next to the class name)

3.The Spring Boot app will start, and you should see:

Tomcat started on port(s): 8080

Started InventoryManagementBackendApplication in X seconds

 ---
 ## ✅ You're Good to Go!
 At this point, your backend application is up and running. You can now start writing tests.
 

