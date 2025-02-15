# Hospital Blood Bank Inventory Management

## 📖 Overview
The **Hospital Blood Bank Inventory Management System** is a Java-based application designed to efficiently manage blood bank inventories within a hospital. This system facilitates blood donation tracking, inventory monitoring, and blood distribution to ensure timely availability of blood for patients in need.

## 🚀 Features

### 1. Donor Management
- **Donor Registration:** Captures donor details including name, contact, blood type, and eligibility.
- **Donation Tracking:** Maintains records of donation history and intervals to ensure eligibility compliance.
- **Eligibility Verification:** Tracks health status and ensures compliance with donation regulations.

### 2. Inventory Management
- **Blood Stock Monitoring:** Real-time tracking of available blood units categorized by type and component.
- **Expiration Alerts:** Alerts administrators about blood units nearing expiration to prevent wastage.
- **Automated Stock Updates:** Updates inventory dynamically upon blood donation and issuance.

### 3. Request and Distribution Management
- **Hospital Blood Requests:** Enables departments to submit blood requests for patients.
- **Approval & Processing:** Ensures requests are fulfilled based on priority and availability.
- **Blood Unit Allocation:** Streamlines allocation and maintains transaction history.

### 4. Reporting & Analytics
- **Donation & Usage Reports:** Generates reports on blood stock trends, donation rates, and usage statistics.
- **Donor Analysis:** Provides insights into donor activity for recruitment and retention strategies.
- **Inventory Insights:** Helps administrators make data-driven decisions regarding stock levels and demand.

## 🛠️ Technologies Used
- **Programming Language:** Java
- **Database Management System:** MySQL (or PostgreSQL)
- **User Interface:** Java Swing / JavaFX
- **Development Environment:** NetBeans IDE
- **Build Automation:** Apache Ant
- **Database Connectivity:** Java Database Connectivity (JDBC)

## 📂 Project Structure
```
Hospital-Blood-Bank-Inventory-Management/
│-- src/                # Java source code
│-- nbproject/          # NetBeans project configuration files
│-- build.xml           # Apache Ant build script
│-- manifest.mf         # Manifest file for JAR execution
│-- dist/               # Compiled JAR and dependencies
│-- Images/             # UI mockups and icons
│-- README.md           # Project documentation
```

## 🎯 Setup and Deployment

### Prerequisites
- Install **Java Development Kit (JDK)**.
- Install **NetBeans IDE** (recommended for development).
- Install **Apache Ant** for build automation.
- Install **MySQL** or **PostgreSQL** for database management.

### Database Setup
1. Open **phpMyAdmin** or your preferred database management tool.
2. Create a new database named `bloodbank`.
3. Update the database connection details in the Java source code (`JDBC` configurations).

### Running the Application
1. Clone the repository:
   ```bash
   git clone https://github.com/sherurox/Hospital-Blood-Bank-Inventory-Management.git
   ```
2. Open the project in **NetBeans IDE**.
3. Build the project using **Apache Ant** (`build.xml`).
4. Run the application using the compiled **JAR** file located in the `dist/` directory.

## 📌 Future Enhancements
- Implement **role-based access control** (separate admin and staff access levels).
- Integrate **cloud-based database solutions** for scalability.
- Introduce **SMS/email notifications** for donors and hospital staff.
- Develop a **web-based UI** for remote accessibility.

## 🤝 Contribution
Contributions are welcome! Feel free to fork this repository, submit pull requests, or report issues.

## 📄 License
This project is open-source under the [MIT License](LICENSE).

