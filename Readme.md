
#  Handsman Threads - Salesforce Implementation

This project demonstrates a complete **Salesforce Lightning Application** implementation for a fictional apparel company, **Handsman Threads**. The goal is to build a scalable, secure, and automated CRM system—from scratch—covering custom objects, security setup, automation with Flow and Apex, and a user-friendly Lightning App.

 Based on: Handsman Threads Tutorial (Salesforce End-to-End Project)

---

##  Features Implemented

###  Custom Data Model

- **Custom Objects**: `Customer`, `Product`, `Order`, `Inventory`, `Marketing Campaign`
- **Fields**:
  - Picklists, Currency, and Formula fields (e.g., `Full Name`, `Stock Status`)
- **Relationships**:
  - Lookup and Master-Detail relationships to maintain referential integrity

---

###  Custom Lightning App

- Branded **"Handsman Threads"** Lightning App
- Includes tabs for custom objects and standard components (Reports, Dashboards)
- Clean UI experience for users

---

###  Data Integrity & Security

- **Validation Rules**: Ensure proper email formats, positive stock/order values, etc.
- **Security Model**:
  - Custom **Profiles**, **Role Hierarchy**, and individual **User accounts**
- **Permission Sets**: Fine-grained access control for:
  - Sales Team
  - Inventory Managers
  - Marketing Users

---

###  Business Process Automation

####  Email Automation

- **Templates**: Order Confirmation, Low Stock Alert
- **Letterhead**: Branded Handsman Threads style
- **Alerts**: Triggered on order or inventory events

####  Flows (No-Code Automation)

- **Record-Triggered Flow**:
  - Auto-email confirmation on new orders
  - Low stock alert to inventory team
- **Scheduled Flow**:
  - Daily loyalty status update for customers

####  Apex Triggers

- Calculate `Total Amount` on orders
- Deduct inventory when order is confirmed

####  Batch Apex

- Bulk inventory update job for efficient processing

---

##  Modules Covered 

1. **Initial Setup** – Create and configure a new Salesforce Developer Org  
2. **Data Model Design** – Objects, fields, relationships  
3. **App Assembly** – Using App Manager to bundle the solution  
4. **Validation & Formulas** – Business logic and calculated fields  
5. **User Access** – Roles, Profiles, Permission Sets  
6. **Email Templates & Alerts** – Automated communications  
7. **Flow Automation** – Scheduled and triggered workflows  
8. **Advanced Apex** – Real-time and batch processing logic  

---

##  Technologies Demonstrated

- **Salesforce Lightning Experience**
- **Salesforce Flow Builder**
- **Apex** (Triggers & Batch Classes)
- **SOQL** (Salesforce Object Query Language)
- **Data Loader / Import Wizard** *(for sample data handling)*

---

##  Deployment Notes

>  Before deploying this app in a real org, ensure:
- Users are assigned correct Profiles & Permission Sets
- Validation Rules match business expectations
- Email Deliverability is set to "All Email"
- Batch classes are tested in Sandbox

___

##DEMO Video Link :

--https://drive.google.com/file/d/1FBJh6g8gZOmVpCdNtggxB4ZKjMNY0S_O/view?usp=sharing

---


