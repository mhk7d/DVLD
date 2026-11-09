# 🚗 Driving & Vehicle Licensing Department (DVLD) System

A robust enterprise-level desktop application built with C# and MS SQL Server to digitize and automate driver licensing services, test scheduling, and vehicle application processing.

---

## 🏗️ System Architecture

The application is engineered using a strict **3-Tier Architecture** pattern to achieve high modularity, scalability, and clean separation of concerns:

1. **Presentation Layer (WinForms):** 
   - Manages UI controls, user interaction, input validation, and event routing.
   - Built with custom reusable controls (e.g., Person Info Cards, License Cards).

2. **Business Logic Layer (BLL):**
   - Enforces domain logic, application rules, constraints, and data transformations.
   - Decoupled from UI and data access logic using C# class libraries.

3. **Data Access Layer (DAL):**
   - Handles direct communication with Microsoft SQL Server using **ADO.NET**.
   - Implements parameterized SQL queries to prevent SQL Injection attacks and ensure database security.

---

## ✨ Core Features & Workflows

- **People & User Management:** Complete CRUD operations, ID card photo management, and dynamic user permissions.
- **Driving License Services:**
  - First-time local driving license applications.
  - International driving license issuance.
  - License renewals and replacements (for lost or damaged licenses).
  - License detaining and release system with fee management.
- **Multi-Stage Driving Tests:**
  - Appointments scheduling and automated result tracking for **Vision**, **Written**, and **Street** tests.
- **Application & Fee Configuration:** Centralized control over application types, test fees, and administrative parameters.

---

## 🛠️ Tech Stack

- **Language:** C# (.NET Framework)
- **UI Framework:** Windows Forms (WinForms)
- **Database:** Microsoft SQL Server
- **Data Access:** ADO.NET
- **Architecture Pattern:** 3-Tier Architecture (Presentation, BLL, DAL)

---

## 🚀 Getting Started

### Prerequisites
- Visual Studio 2022 (with .NET Desktop Development workload)
- Microsoft SQL Server & SQL Server Management Studio (SSMS)

### Setup Instructions
1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/mhk7d/DVLD.git](https://github.com/mhk7d/DVLD.git)
