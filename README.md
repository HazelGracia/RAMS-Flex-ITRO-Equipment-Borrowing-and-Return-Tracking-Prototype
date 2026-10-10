# RAMS Flex: ITRO Equipment Borrowing and Return Tracking Prototype

> **Asia Pacific College (APC) — Information Technology Resource Office (ITRO)**  
> **Academic Project | AY 2026-2027**  
> **Prepared by Team TriTechPlus**

---

## 📌 Project Overview
RAMS Flex is an academic web-based prototype demonstrating a centralized digital workflow for equipment borrowing and return management. It transitions ITRO's current manual processes (separate messages, paper forms, and Excel-based inventories) into a streamlined, secure, and trackable online system. 

*Note: RAMS Flex is an academic prototype intended for ITRO workflow review and testing using simulated data; it is not an official live operational system or integrated into APC production databases.*

---

## 🛠️ Technology Stack & Architecture
The system is built on a reliable, low-complexity Monolithic architecture designed for a 6-week academic delivery timeline:
* **Hosting Environment:** AWS Lightsail (Ubuntu, Static IP, LAMP blueprint)
* **Web Server:** Apache
* **Backend Application:** PHP
* **Database:** MySQL
* **Version Control & Tracking:** GitHub & Jira (Project RFD)

---

## 👥 User Roles & Key Features
The prototype supports four simulated user roles, incorporating LDAP-concept access control:
1. **Borrowers (Students/Faculty):** Browse equipment catalogs, check item availability, evaluate eligibility, submit borrowing tickets, track requests via "My Requests", and utilize a self-service AI chatbot.
2. **Custodians (ITRO Staff):** Review/approve requests, perform release inspections with borrower acknowledgment, process returns, update inventory status automatically, and manage overdue queues.
3. **Administrators:** Manage asset types, categories, individual unit conditions, and system configuration rules.
4. **Auditors:** Review role-restricted audit trails, KPI dashboards, and system-generated reports.

---
