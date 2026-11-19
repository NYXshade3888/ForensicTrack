# 🔍 ForensicTrack
### Digital Forensics Case and Evidence Management System

ForensicTrack is a web-based Digital Forensics Case and Evidence Management System designed to help investigators manage forensic cases, maintain digital evidence records, document investigation activities, and track the chain of custody.

The system provides a centralized platform for managing forensic investigations while maintaining organized records of cases and their associated evidence.

---

## 🚀 Features

- **User Authentication:** Secure login and registration functionality.
- **Role-Based Access:** Separate Admin and Investigator roles.
- **Case Management:** Create, view, update, and manage forensic cases.
- **Evidence Management:** Record and organize evidence associated with cases.
- **Case Notes:** Maintain investigation notes and updates.
- **Chain of Custody:** Track evidence handling activities and custody records.
- **User Management:** Manage system users and their roles.
- **Investigation Overview:** View investigation-related information in one place.

---

## 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| Java | Backend programming |
| JSP | Dynamic web pages |
| Jakarta Servlets | Request handling |
| Spring Framework | Dependency injection |
| Hibernate ORM | Database interaction |
| MySQL | Database management |
| Maven | Project and dependency management |
| Apache Tomcat 10.1 | Web application server |
| NetBeans IDE | Development environment |
| HTML, CSS, JavaScript | Frontend development |

---

## 🗄️ Database Structure

Database name: `forensictrack_db`

Main database tables:

- `users`
- `cases`
- `evidence`
- `case_notes`
- `chain_of_custody`

These tables maintain user information, forensic case details, evidence records, investigation notes, and evidence custody history.

---

## 💻 Installation and Setup

### Prerequisites

Make sure the following software is installed:

- Java JDK
- Apache NetBeans IDE
- Apache Tomcat 10.1
- MySQL Server or XAMPP
- Apache Maven

### 1. Clone the Repository

```bash
git clone https://github.com/NYXshade3888/ForensicTrack.git
```

### 2. Open the Project

1. Open Apache NetBeans.
2. Select **File → Open Project**.
3. Choose the cloned ForensicTrack project folder.
4. Wait for Maven dependencies to load.

### 3. Configure the Database

1. Start MySQL using XAMPP or your MySQL server.
2. Open phpMyAdmin.
3. Create a database named:

```sql
CREATE DATABASE forensictrack_db;
```

4. Import or execute the project's database schema.
5. Configure the database connection settings in the project's Hibernate configuration.

Make sure the database URL, username, and password match your local MySQL configuration.

### 4. Configure Apache Tomcat

1. Add Apache Tomcat 10.1 to NetBeans.
2. Open the project properties.
3. Select **Run → Server**.
4. Choose Apache Tomcat 10.1.

### 5. Build and Run

1. Right-click the project.
2. Select **Clean and Build**.
3. Once the build succeeds, select **Run**.
4. Open the application in your browser.

---

## 📂 Project Modules

| Module | Description |
|---|---|
| Authentication | Login and registration |
| Dashboard | Investigation overview |
| Case Management | Forensic case records |
| Evidence Management | Evidence information |
| Case Notes | Investigation documentation |
| Chain of Custody | Evidence handling history |
| User Management | User and role administration |

---

## 🔐 User Roles

**Administrator**
- Manage users and system access.
- Oversee forensic case records.
- Manage investigator accounts.

**Investigator**
- Access assigned investigation functionality.
- Manage case-related information.
- Record evidence and investigation notes.

---

## 🎯 Project Objective

The main objective of ForensicTrack is to simplify digital forensic investigation management by providing an organized system for case documentation, evidence tracking, and chain-of-custody record management.

---

## 👨‍💻 Developer

**Akshith Aruru**

GitHub: [@NYXshade3888](https://github.com/NYXshade3888)

Project Repository: [ForensicTrack](https://github.com/NYXshade3888/ForensicTrack)

---

## 📜 License

This project is currently available for educational and demonstration purposes. A formal license can be added if required.
