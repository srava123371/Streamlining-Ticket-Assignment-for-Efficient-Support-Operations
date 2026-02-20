# 🎫 Streamlining Ticket Assignment for Efficient Support Operations

A ServiceNow-based automation project designed to streamline support ticket routing using custom tables, roles, groups, ACL, and Flow Designer.

---
## 👨‍💻 Team Members

- G. Sravani – Users & Groups Creation  
- G. Chandana – Roles & Custom Table Configuration  
- J. Meghana – Role & User Assignment  
- M. Sanjana – ACL Configuration  
- S. Swathi – Flow Automation  

---

## 🎥 Demo

📌 Demo Video Link: (Add your demo video link here)

---

## 📌 Project Overview

This project automates ticket assignment in ServiceNow.  
When a user creates a ticket and selects an issue type, the system automatically assigns the ticket to the correct support group using Flow Designer automation.

---

## ✨ Key Features

- Custom table: **Operations Related**
- Automated ticket assignment
- Role-based access control
- ACL security implementation
- Flow Designer automation
- Reduced manual effort

---

## 🛠 Technologies Used

| Layer | Technology |
|-------|------------|
| Platform | ServiceNow (PDI) |
| Automation | Flow Designer |
| Database | Custom Table |
| Security | Roles & ACL |

---

## ⚙️ How to Run the Project

### Step 1 — Create ServiceNow Instance
1. Go to https://developer.servicenow.com  
2. Create a Personal Developer Instance (PDI).

### Step 2 — Import Update Set
1. Navigate to **System Update Sets → Retrieved Update Sets**  
2. Click **Import Update Set from XML**  
3. Upload the project update set file  
4. Click **Preview Update Set**  
5. Click **Commit Update Set**

### Step 3 — Verify Components
Ensure the following exist:
- Operations Related table
- Users and Groups
- Roles
- ACL rules
- Flows:
  - Regarding Certificates
  - Regarding Platform

### Step 4 — Execute Project
1. Open **Operations Related → New**
2. Enter ticket details
3. Select Issue type
4. Click **Submit**

### Step 5 — Validate Automation
- Regarding Certificates → Assigned to Certificate Group  
- Platform/Login/404/User Expired → Assigned to Platform Group  

---

## 🧪 Testing

### Functional Testing
- Verified users, groups, and roles
- Checked table configuration
- Validated ACL permissions

### Flow Testing
- Created test tickets
- Verified automatic group assignment
- Confirmed flow execution

### Security Testing
- Tested role-based access
- Verified restricted access for unauthorized users

---

## 🔐 Authentication

Role-based access control implemented using ServiceNow roles and ACL.

---

## 🚀 Future Enhancements

- Email notifications
- SLA tracking
- Dashboard reporting
- Approval workflows

---

## 📌 Conclusion

This project successfully automates ticket assignment in ServiceNow using Flow Designer, improving operational efficiency, reducing manual work, and ensuring proper ticket routing.

---
