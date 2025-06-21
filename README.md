# Vehicle Manager

A simple Java desktop application for managing your vehicle-related data — including maintenance intervals, service history, expenses, and receipts.

Built with:
- Java 21
- Spring Boot
- Vaadin (UI)
- Maven

---

## Features

- Manage multiple vehicles
- Track service history and maintenance intervals
- Log expenses and attach receipts
- Works offline, with a clean browser-based UI
- Local data persistence

---

## How to Run

### 1. Install Java 21+

Download and install the **Java 21 JDK** from one of the following sources:

- [https://jdk.java.net/21/](https://jdk.java.net/21/)
- [https://adoptium.net/temurin/releases/?version=21](https://adoptium.net/temurin/releases/?version=21)

Verify that `java` is available in your terminal:

```bash
java --version
```

### 2. Run the Application

```bash
java -Dbase.path="PATH_TO_WORKING_DIR" -jar vehiclemanagement-0.1.jar
```

Replace `PATH_TO_WORKING_DIR` with the full path to the folder where the application expects the following subdirectories:

- `` `persistence/` `` – where your local vehicle data is stored
- `` `target/` `` – compiled application and resources  
- `` `node/` `` – frontend-related files

### 3. Access the Application

Once the application is running, open your browser and visit [`http://localhost:9493`](http://localhost:9493) to access the application.

---

## Future Improvements

Planned features for upcoming versions:

- **Import/Export vehicle data**  
  Support for exporting and importing vehicle history and service records as `.zip` files, allowing easier backup, sharing, and migration between systems.

- **Filter documents by type**
  Add the ability to filter and view attached documents based on their type (e.g., receipts, service invoices), improving navigation without changing the existing organization.
