# BD_Aparcamiento - Parking Management System

A desktop application developed in **Java** using the **Swing** library for the graphical user interface (GUI) and a **MySQL** database for data persistence. This system is designed to manage vehicle entries, exits, and record-keeping for a parking facility.

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

## Execution
1. Create the database using scriptBaseDeDatos.txt.
2. Fill it using tuplas.txt
3. Execute Java project.
   
##  Project Structure
Inside Aparcamiento3E.zip:
* `src/`: Contains the Java source code files.
    * `gui/`: Swing forms and UI components.
    * `conexionBBDD/`: Connection classes and SQL queries.
    * `logic/`: Business logic and vehicle models.
* `.jar files/`: External libraries.
In  `scriptBaseDeDatos.txt/`: creation of SQL tables
In `tuplas.txt/`: insertion of data.

