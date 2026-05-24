

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

|EPIC ID|EPIC Name|Description|
|---|---|---|
|E1|User Management|Manage users and authentication|
|E2|Donation Management|Manage donated items and records|
|E3|Inventory Management|Track and manage inventory stock|
|E4|Distribution Management|Manage distribution of donated items|
|E5|Reporting & Dashboard|Generate reports and view statistics|

---

# MRFs (Minimally Releasable Features)

These are smaller features under each EPIC.

---

# EPIC E1 — User Management

|MRF ID|MRF Name|Description|
|---|---|---|
|MRF 1.1|User Login|Allow users to log into the system|
|MRF 1.2|Role Management|Manage Admin, Inventory Staff, and Volunteers|
|MRF 1.3|User Profile Management|Update user information|

---

# EPIC E2 — Donation Management

|MRF ID|MRF Name|Description|
|---|---|---|
|MRF 2.1|Add Donations|Record donated items|
|MRF 2.2|View Donation History|Display past donation records|
|MRF 2.3|Donation Categories|Organize donations by category|

---

# EPIC E3 — Inventory Management

|MRF ID|MRF Name|Description|
|---|---|---|
|MRF 3.1|Add Inventory Items|Add new inventory items|
|MRF 3.2|Update Inventory Stock|Update stock quantities|
|MRF 3.3|Inventory Search|Search available items|
|MRF 3.4|Low Stock Alerts|Notify low inventory levels|

---

# EPIC E4 — Distribution Management

|MRF ID|MRF Name|Description|
|---|---|---|
|MRF 4.1|Record Distribution|Record distributed items|
|MRF 4.2|Beneficiary Records|Store beneficiary details|
|MRF 4.3|Distribution History|View previous distributions|

---

# EPIC E5 — Reporting & Dashboard

|MRF ID|MRF Name|Description|
|---|---|---|
|MRF 5.1|Dashboard Overview|Display system statistics|
|MRF 5.2|Donation Reports|Generate donation reports|
|MRF 5.3|Inventory Reports|Generate inventory reports|
|MRF 5.4|Distribution Reports|Generate distribution reports|

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
As an Admin,
I want to manage system users,
So that authorized users can access the system securely.
```

---

## User Story 2

```text
As a Volunteer,
I want to record donated items,
So that donations are tracked properly.
```

---

## User Story 3

```text
As an Inventory Staff member,
I want to update stock quantities,
So that inventory records remain accurate.
```

---

## User Story 4

```text
As a Volunteer,
I want to record distributed items,
So that donation distributions can be monitored.
```

---

## User Story 5

```text
As an Admin,
I want to generate reports,
So that I can monitor charity operations efficiently.
```



# Conclusion 

The Charity Inventory Management System is a practical and socially impactful software solution that helps charities and NGOs efficiently manage donations and distributions. The system improves operational efficiency, transparency, and accountability while ensuring resources reach beneficiaries effectively. This project demonstrates strong software engineering concepts including database management, inventory tracking, role-based systems, and reporting functionalities.