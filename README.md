# 🚀 Azure VM & SQL Server 2025 Express Deployment

## 👨‍🎓 Student
Aziz Eke

---

## 📌 Project Overview

This project demonstrates the deployment and configuration of a Windows-based Virtual Machine in Microsoft Azure, including SQL Server 2025 Express installation and Azure File Share integration.

The goal of this assignment was to gain hands-on experience with cloud infrastructure, remote access, database management, and cloud storage services.

---

## ☁️ Project Scope

During this project, I completed the following tasks:

- Created a Virtual Machine in Azure Portal
- Connected to the VM via Remote Desktop (RDP)
- Installed SQL Server 2025 Express
- Installed SQL Server Management Studio (SSMS)
- Configured SQL Server connection
- Created a database and tables
- Created an Azure File Share
- Uploaded and deleted files in Azure File Storage
- Documented encountered issues and applied solutions

---

## 🖥️ Azure Virtual Machine Setup

- Resource Group created
- Windows Server selected
- Public IP configured
- RDP (Port 3389) enabled
- Basic security configuration applied

---

## 🗄️ SQL Server Installation

### Installed:
- SQL Server 2025 Express Edition
- SQL Server Management Studio (SSMS)

### Configuration:
- Connected using Windows Authentication
- Verified SQL Server service status
- Enabled TCP/IP (if applicable)

---

## 🗃️ Database Implementation

Inside SSMS:

- Created a new database
- Created at least one table
- Inserted sample data
- Queried data successfully using SELECT statements

Example SQL Query:

```sql
CREATE DATABASE SchoolDB;

USE SchoolDB;

CREATE TABLE Students (
    Id INT PRIMARY KEY IDENTITY(1,1),
    Name NVARCHAR(100),
    Age INT
);

INSERT INTO Students (Name, Age)
VALUES ('Ali', 22);

SELECT * FROM Students;
