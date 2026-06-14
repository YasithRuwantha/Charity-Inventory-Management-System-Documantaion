

# Summary

The Charity Inventory Management System is a web-based application designed to help charity organizations manage donations, inventory, donors, and item distributions efficiently.

Many charities currently manage donated goods manually using paper records or spreadsheets, which can lead to inventory errors, missing records, and inefficient distribution processes. This system provides a digital solution to organize and track all charity operations in one platform.


## Main users

![[Pasted image 20260524114455.png]]


# Functional Requirements

## 1. User Authentication & Management

- The system shall allow Admin, Inventory Staff, and Volunteers to log in securely.
    
- The system shall provide role-based access control for different user types.
    
- The system shall allow the Admin to manage user accounts.
    

---

## 2. Donation Management

- The system shall allow Volunteers to record donated items.
    
- The system shall store donation details including item name, category, quantity, and donation date.
    
- The system shall maintain donation history records.
    

---

## 3. Inventory Management

- The system shall allow Inventory Staff to add, update, and remove inventory items.
    
- The system shall track available stock quantities.
    
- The system shall display current inventory status.
    
- The system shall provide low-stock alerts for critical items.
    

---

## 4. Distribution Management

- The system shall allow Volunteers to record distributed items.
    
- The system shall store beneficiary details and distribution records.
    
- The system shall automatically update inventory after distributions.
    

---

## 5. Reporting & Dashboard

- The system shall generate donation reports.
    
- The system shall generate inventory reports.
    
- The system shall generate distribution reports.
    
- The system shall display dashboard statistics and summaries.
    

---

## 6. Search & Filter Functions

- The system shall allow users to search inventory items.
    
- The system shall allow filtering donations and distributions by date or category.
    

---

## 7. Notification & Alerts

- The system shall notify users about low inventory levels.
    
- The system shall display alerts for expired or outdated inventory records if applicable.


# EPICs

EPICs are the major modules/features of the system.

| EPIC ID | EPIC Name               | Description                          |
| ------- | ----------------------- | ------------------------------------ |
| E1      | User Management         | Manage users and authentication      |
| E2      | Donation Management     | Manage donated items and records     |
| E3      | Inventory Management    | Track and manage inventory stock     |
| E4      | Distribution Management | Manage distribution of donated items |
| E5      | Reporting & Dashboard   | Generate reports and view statistics |

---

# MRFs (Minimally Releasable Features)

These are smaller features under each EPIC.

## EPIC E1 — User Management

|MRF ID|MRF Name|Description|User Story|Subtasks|
|-|-|-|-|-|
|MRF 1.1|User Login|Allow users to log into the system|As a registered user, I want to log into the system securely so that I can access my assigned dashboard and features.|Design login UI form<br />Implement authentication logic<br />Add error handling for invalid credentials|
|MRF 1.2|User Register|Allow users to register into the system|As a new user, I want to register an account so that I can access the system based on my role.|Create registration form<br />Validate user input<br />Save user details securely|
|MRF 1.3|Role Management|Manage Admin, Inventory Staff, and Volunteers|As an admin, I want to assign roles to users so that access is controlled based on responsibilities.|Create role management interface<br />Assign/update roles <br />Restrict access by role|
|MRF 1.4|User Profile Management|Update user information|As a user, I want to update my profile information so that my details remain accurate.|Create profile page<br />Implement update functionality<br />Validate and save data|

## EPIC E2 — Donation Management

|MRF ID|MRF Name|Description|User Story|Subtasks|
|-|-|-|-|-|
|MRF 2.1|Add Donations|Record donated items|As a staff member, I want to record donated items so that donations are tracked in the system.|Create donation form<br />Save donation records<br />Validate donation inputs|
|MRF 2.2|View Donation History|Display past donation records|As an admin, I want to view all past donations so that I can monitor donation activities.|Create history view<br />Fetch donation records<br />Add filtering options|
|MRF 2.3|Donation Categories|Organize donations by category|As a staff member, I want to categorize donations so that items are organized properly.|Create category module<br />Assign categories<br />Display categorized list|

## EPIC E3 — Inventory Management

|MRF ID|MRF Name|Description|User Story|Subtasks|
|-|-|-|-|-|
|MRF 3.1|Add Inventory Items|Add new inventory items|As an inventory staff member, I want to add new items so that stock is updated in the system.|Create inventory form<br />Insert item into database<br />Validate item details|
|MRF 3.2|Update Inventory Stock|Update stock quantities|As an inventory manager, I want to update stock levels so that inventory remains accurate.|Create update interface<br />Implement stock updates<br />Log stock changes|
|MRF 3.3|Inventory Search|Search available items|As a user, I want to search inventory items so that I can quickly find available stock.|Implement search bar<br />Add search functionality<br />Display filtered results|
|MRF 3.4|Low Stock Alerts|Notify low inventory levels|As an inventory manager, I want to receive low stock alerts so that I can restock items on time.|Define thresholds<br />Implement alert logic<br />Display dashboard notifications|

## EPIC E4 — Distribution Management

|MRF ID|MRF Name|Description|User Story|Subtasks|
|-|-|-|-|-|
|MRF 4.1|Record Distribution|Record distributed items|As a staff member, I want to record distributed items so that donations given out are tracked.|Create distribution form<br />Deduct inventory stock<br />Save records|
|MRF 4.2|Beneficiary Records|Store beneficiary details|As an admin, I want to store beneficiary details so that distributions are properly tracked.|Create registration form<br />Store beneficiary data<br />Link to distributions|
|MRF 4.3|Distribution History|View previous distributions|As an admin, I want to view distribution history so that I can track past aid activities.|Create history view<br />Fetch data<br />Add filters|

## EPIC E5 — Reporting & Dashboard

|MRF ID|MRF Name|Description|User Story|Subtasks|
|-|-|-|-|-|
|MRF 5.1|Dashboard Overview|Display system statistics|As a user, I want to view a dashboard summary so that I can understand system activity at a glance.|Design dashboard UI<br />Display statistics<br />Add real-time updates|
|MRF 5.2|Donation Reports|Generate donation reports|As an admin, I want to generate donation reports so that I can analyze donation trends.|Create reporting module<br />Add filters<br />Export PDF/Excel|
|MRF 5.3|Inventory Reports|Generate inventory reports|As an inventory manager, I want to generate inventory reports so that I can track stock status.|Build report generator<br />Include stock data<br />Export reports|
|MRF 5.4|Distribution Reports|Generate distribution reports|As an admin, I want to generate distribution reports so that I can monitor aid distribution efficiency.|Create reporting module<br />Summarize distributions<br />Export reports|

---

# 3. Agile Scrum Workflow

---

# Product Backlog

The Product Backlog contains all features required for the system.

### Example Backlog Items

- User login
    
- Add donations
    
- Inventory tracking
    
- Distribution records
    
- Reports dashboard
    

---

# Sprint Planning

The project is divided into multiple sprints.

---

# Sprint 1 — Authentication & User Management

### Tasks

- Login system
    
- User roles
    
- Dashboard setup
    

### Related EPIC

E1 — User Management

---

# Sprint 2 — Donation Management

### Tasks

- Add donations
    
- Donation categories
    
- Donation history
    

### Related EPIC

E2 — Donation Management

---

# Sprint 3 — Inventory Management

### Tasks

- Add inventory items
    
- Update stock
    
- Search inventory
    
- Low stock alerts
    

### Related EPIC

E3 — Inventory Management

---

# Sprint 4 — Distribution Management

### Tasks

- Record distributions
    
- Beneficiary records
    
- Distribution history
    

### Related EPIC

E4 — Distribution Management

---

# Sprint 5 — Reports & Final Testing

### Tasks

- Dashboard statistics
    
- Reports generation
    
- System testing
    
- Bug fixing
    

### Related EPIC

E5 — Reporting & Dashboard

---

# 4. Example User Stories

---

## User Story 1

```text
As a registered user,
I want to log into the system securely,
So that I can access my assigned dashboard and features.
```

---

## User Story 2

```text
As a staff member,
I want to record donated items,
So that donations are tracked in the system.
```

---

## User Story 3

```text
As an inventory staff member,
I want to add new items,
So that stock is updated in the system.
```

---

## User Story 4

```text
As a staff member,
I want to record distributed items,
So that donations given out are tracked.

```

---

## User Story 5

```text
As a user,
I want to view a dashboard summary,
So that I can understand system activity at a glance.
```



# Conclusion 

The Charity Inventory Management System is a practical and socially impactful software solution that helps charities and NGOs efficiently manage donations and distributions. The system improves operational efficiency, transparency, and accountability while ensuring resources reach beneficiaries effectively. This project demonstrates strong software engineering concepts including database management, inventory tracking, role-based systems, and reporting functionalities.
