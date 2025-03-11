# osTicket Configuration Guide

This guide provides step-by-step instructions to configure **osTicket** after installation.

---

## 1. Access osTicket  
### Admin & Analyst Login  
- **Admin/Analyst Panel:** [http://localhost/osTicket/scp/login.php](http://localhost/osTicket/scp/login.php)  
- **End Users Portal:** [http://localhost/osTicket](http://localhost/osTicket)  

---

## 2. Understanding the Panels  
- **Admin Panel:** Used for system configuration, roles, departments, teams, and SLA settings.  
- **Agent Panel:** Used for managing users, tickets, and general help desk operations.  

---

## 3. Configure Roles (Grouping Permissions)  
📍 **Admin Panel → Agents → Roles**  
- **Supreme Admin** *(Full Access to all settings and configurations)*  

---

## 4. Configure Departments (Ticket Visibility)  
📍 **Admin Panel → Agents → Departments**  
- **SysAdmins** *(Manages system-related tickets)*  
- **Help Desk** *(Handles general user issues)*  
- **Networking** *(Manages network-related tickets)*  

---

## 5. Configure Teams (Cross-Department Collaboration)  
📍 **Admin Panel → Agents → Teams**  
- **Online Banking** *(Pulls agents from different departments to work on specific issues)*  

---

## 6. Configure Ticket Creation Rules  
📍 **Admin Panel → Settings → User Settings**  
- **Allow anyone to create tickets:** ✅ *(Unchecked: Users must register to submit tickets)*  
- **Require registration:** ✅ *(Users must log in before submitting a ticket)*  

---

## 7. Configure Agents (Support Staff)  
📍 **Admin Panel → Agents → Add New**  
| Name  | Department  |  
|-------|------------|  
| Jane  | SysAdmins  |  
| John  | Support    |  

---

## 8. Configure Users (Customers)  
📍 **Agent Panel → Users → Add New**  
| Name  |  
|-------|  
| Karen |  
| Ken   |  

---

## 9. Configure Service Level Agreements (SLA)  
📍 **Admin Panel → Manage → SLA**  
| SLA Level | Grace Period | Schedule  |  
|-----------|-------------|-----------|  
| Sev-A     | 1 hour      | 24/7      |  
| Sev-B     | 4 hours     | 24/7      |  
| Sev-C     | 8 hours     | Business Hours |  

---

## 10. Configure Help Topics (For User Ticket Creation)  
📍 **Admin Panel → Manage → Help Topics**  
- **Business Critical Outage**  
- **Personal Computer Issues**  
- **Equipment Request**  
- **Password Reset**  
- **Other**  

---

## 🎉 Configuration Complete!  
Your **osTicket** system is now fully set up and ready for use. 🚀  
