# Hospital Management System

**Loyal** is a Java-based mini hospital management system designed for educational and practical use.  
It demonstrates how core modules of a medical center or clinic can be digitized using simple Java and NetBeans.  
The system focuses on **streamlining everyday tasks** like managing doctors, patients, appointments, prescriptions, and medical inventory — all through clear, modular code.

---

## 📌 Key Modules and What They Do

**🔐 User Authentication**  
- Basic login system to secure access to the management system.  
- Prevents unauthorized use of the application.

**🩺 Doctor Management**  
- Add new doctor profiles with relevant details.  
- Store and update doctor information for easy channeling.

**👥 Patient Management**  
- Register patients into the system.  
- Maintain patient records for future visits and prescriptions.

**📅 Appointment (Channeling) System**  
- Schedule appointments (channels) between patients and doctors.  
- View and manage scheduled channels for efficient hospital flow.

**💊 Prescription Management**  
- Record and view prescriptions issued by doctors.  
- Link prescriptions to patient records for tracking treatment history.

**📦 Inventory & Items**  
- Keep track of medical items and inventory stock.  
- Add, update, and manage medicines or equipment used in the hospital.

**📊 Reporting**  
- Simple reports for doctors, patients, channels, or prescriptions.  
- Provides insights into hospital operations in a basic, easy-to-read format.

---

## 🛠️ Technologies Used

**Java SE:**  
The entire application is written in Java using object-oriented programming principles. It includes multiple classes to represent real-world hospital entities like doctors, patients, appointments, and prescriptions.

**Java Swing:**  
Basic graphical user interfaces (if used) are implemented using Java Swing components. These handle forms, dialogs, and simple input screens for interacting with the user in a desktop environment.

**SQL (MySQL via XAMPP):**  
The project uses a MySQL database hosted on a local XAMPP server to store and manage hospital data. Java connects to the database using **JDBC (Java Database Connectivity)**, which executes SQL queries for operations like insert, update, and retrieve. The database schema is managed using phpMyAdmin provided by XAMPP.

**Apache Ant:**  
The `build.xml` is used to compile and build the project automatically within NetBeans.

---

