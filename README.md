# BD_Aparcamiento - Parking Management System

A desktop application developed in **Java** using the **Swing** library for the graphical user interface (GUI) and a **MySQL** database for data persistence. This system is designed to manage vehicle entries, exits, and record-keeping for a parking facility. Developed by a team of 5 members, for more info see Memoria.pdf

##  Features

* **Vehicle Registration:** Record vehicle entry with license plate, type, and entry time.
* **Real-time Database:** Integration with MySQL to store and retrieve parking records.
* **User Interface:** User-friendly forms built with Java Swing (JFrame, JPanel, etc.).
* **Cost Calculation:** Automatic calculation of fees based on stay duration.
* **Search and Reports:** Filter and view historical data of parked vehicles. Reports of historical data in PDF.

##  Technologies Used

* **Language:** Java (JDK 8 or higher)
* **GUI Library:** Java Swing / AWT
* **Database:** MySQL
* **Connectivity:** JDBC (Java Database Connectivity)

##  Prerequisites

Before running the project, ensure you have the following installed:
1.  **Java Development Kit (JDK)**
2.  **MySQL Server**
3.  **MySQL Connector/J** (the .jar driver)
4.  An IDE like **NetBeans, IntelliJ IDEA, or Eclipse**

## Installation
Follow these steps to get the environment ready and run the application.

### 1. Database Configuration
The database structure and initial data are provided in `.txt` files.

1.  **Create the Database:**
    * Open your MySQL terminal or Workbench.
    * Run: `CREATE DATABASE db_aparcamiento;` (or the name specified in your code).
2.  **Create Tables:**
    * Open `scriptBaseDeDatos.txt`.
    * Copy the SQL commands and execute them in your MySQL editor to build the tables.
3.  **Insert Initial Data:**
    * Open `tuplas.txt`.
    * Execute the `INSERT` statements to populate the database.

### 2. Java Environment Setup
1.  **Open the Project:** Import the source folder into your IDE (NetBeans, IntelliJ, or Eclipse).
2.  **Add MySQL Driver:**
    * Ensure the `mysql-connector-java.jar` is added to your project's **Libraries/Classpath**.
3.  **Update Credentials:**
    * Locate the connection class (e.g., `Conexion.java`).
    * Update the `user` and `password` variables to match your local MySQL configuration.

### 3. Running the App
1.  Find the `Main` class (the one containing the `public static void main` method).
2.  Run the file from your IDE or use the terminal:
    ```bash
    java -cp ".;lib/mysql-connector-java.jar" Main
    ```
   
##  Project Structure
Inside Aparcamiento3E.zip:
* `src/`: Contains the Java source code files.
    * `gui/`: Swing forms and UI components.
    * `conexionBBDD/`: Connection classes and SQL queries.
    * `logic/`: Business logic and vehicle models.
* `.jar files/`: External libraries.
In  `scriptBaseDeDatos.txt/`: creation of SQL tables
In `tuplas.txt/`: insertion of data.

