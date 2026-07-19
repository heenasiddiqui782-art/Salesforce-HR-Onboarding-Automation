# HR Onboarding & Provisioning Automation

## 🚀 Project Overview
This project streamlines the employee onboarding process within Salesforce by automating the creation of provisioning tasks. It replaces manual, error-prone workflows with a scalable, automated system that provides real-time visibility into onboarding progress for HR and IT management.

## 💡 The Problem
In many organizations, onboarding is a disjointed process. When a new hire is onboarded, internal teams are often notified via fragmented emails or manual tickets, leading to delays, missing equipment, and poor visibility into completion status.

## 🛠 The Solution
I designed and implemented an automated solution within Salesforce that:
* **Automates Workflows:** Triggers immediate task creation upon the initiation of an onboarding case.
* **Standardizes Provisioning:** Ensures consistent task assignment for every new hire.
* **Visualizes Progress:** Provides a real-time dashboard for management to track completed vs. pending tasks.

---

## 📸 Visual Documentation

### 1. Data Model & Application Experience
This application centers on the `Onboarding_Case__c` custom object, designed to streamline the HR onboarding process. The record page is configured to provide immediate visibility into case details and their associated provisioning tasks.
<img width="960" height="412" alt="P4 ( s2 )" src="https://github.com/user-attachments/assets/2f577a0a-c595-4123-bebd-d9e67fa689e3" />


*The custom Onboarding Case page layout, showing key fields and the integrated Related List for automated Provisioning Tasks.*

### 2. Automation Logic (Flow)
<img width="1920" height="903" alt="P4 ( s1 )" src="https://github.com/user-attachments/assets/b52603b9-f528-4d39-a6b0-e59f46453d78" />

*The Record-Triggered Flow that handles the automated generation of provisioning tasks, reducing manual administrative effort.*

### 3. Reporting Configuration
<img width="960" height="399" alt="P4 ( s3 )" src="https://github.com/user-attachments/assets/aec2757a-3f13-48f4-b463-1f9905873ca3" />

*The custom report configuration used to aggregate data from the provisioning tasks, powering the analytical insights.*

### 4. Executive Dashboard
<img width="960" height="423" alt="P4 ( s4 )" src="https://github.com/user-attachments/assets/126c02d4-1015-4f35-b3c4-3c30a81838ca" />

*The final dashboard providing an at-a-glance view of onboarding status, allowing managers to identify bottlenecks instantly.*

---

## ⚙️ Key Features
- **Scalable:** The automation logic easily supports future additions to the provisioning checklist.
- **Data Integrity:** Maintains a clean parent-child relationship for accurate record-keeping.
- **User-Centric:** Dashboard optimized for high-level status tracking and management oversight.

## 🛠 Technologies Used
- **Salesforce Flow Builder** (Automated Task Creation)
- **Salesforce Reporting & Dashboards** (Data Visualization)
- **Object Modeling** (Custom Objects & Relationships)
- **Salesforce Lightning Experience**

## 📬 Contact
* **Created by:** Heena Siddiqui
* **LinkedIn:** www.linkedin.com/in/heenasiddiqui

---
*Built as part of my Salesforce development journey.*
