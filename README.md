# entra-id-user-management-lab
 Hands-on lab with Microsoft Entra ID (User management, licenses, roles, and bulk import)


 # Microsoft Entra ID – User Management Lab Report

## 👨‍💻 Overview
This project documents my hands-on experience performing essential Identity and Access Administrator tasks using **Microsoft Entra ID (formerly Azure AD)**.

The lab exercises cover:
- User creation and profile configuration
- License assignments
- Role-based access control
- External (B2B) collaboration
- Bulk user import operations

> This is part of my learning journey toward becoming a **Cloud Security Analyst**, with a focus on **IAM** and **Microsoft Entra**.

---

## ✅ Tasks Performed

### 1. Create a New User
- Created user: **Bhogeswar Kalita**
- Configured first name, last name, and usage location
- Stored auto-generated password securely
- Status: ✅ **Successful**

### 2. Login Simulation
- Used InPrivate browsing to simulate first-time login
- Completed MFA setup
- Explored Microsoft Entra user experience
- Status: ✅ **Successful**

### 3. Assign a License *(Challenge Faced)*
- Tried assigning **Power Automate Free** license
- Blocked due to lack of Microsoft 365 Admin Center access
- 🟠 **Lesson Learned**: Admin role access is essential for license assignments

### 4. Invite an External User
- Email: `ExtUser@testemail.com`
- Added welcome message for collaboration scenario
- Status: ✅ **Successful**

### 5. Assign Roles to User
- Assigned:
  - `Attribute Definition Reader` (Eligible)
  - `Attribute Log Reader` (Active, with justification)
- Used both user-based and role-based assignment methods
- Status: ✅ **Successful**

### 6. Bulk User Import *(Issue Identified)*
- Used sample CSV file
- ⚠️ Initial import failed due to mismatch in domain name
- ✅ **Light Bulb Moment**: Organizational users must share the tenant’s domain name
- Status: 🟠 **Partially Successful** (corrected for future)

---

## 🧠 Key Learnings
- Importance of domain consistency for internal users
- Role assignment types: **Active** vs **Eligible**
- Guest users have restricted capabilities
- Admin privileges matter for full access and control

## 💡 Key Takeaways
- Gained real-world understanding of user lifecycle management in Entra ID.
- Recognized the need for domain alignment in enterprise identity design.
- Identified admin role and licensing boundaries across Microsoft platforms.
- Developed critical thinking for troubleshooting IAM misconfigurations.


## 🚀 Why This Project Matters

This lab is part of my intentional roadmap toward becoming an **Identity and Access Management (IAM) Analyst**. Mastering Microsoft Entra ID is foundational, as it powers identity governance in the Microsoft ecosystem.

🔐 IAM is not just about granting access — it's about **governing digital identity at scale**.


---

## 🔐 Tools Used
- Microsoft Entra Admin Center (`https://entra.microsoft.com`)
- Microsoft 365 Admin Center (`https://admin.microsoft.com`)
- CSV template for bulk user creation
- InPrivate browser sessions for simulating first-time user experience

---

## 🏁 Next Steps
- Complete similar tasks using PowerShell and Microsoft Graph API
- Explore advanced Identity Governance features
- Prepare for Microsoft SC-300: Microsoft Identity and Access Administrator** certification.
- Explore advanced IAM tools like SailPoint, Okta, and CyberArk.


## 🙋‍♂️ About Me

I'm transitioning into **cybersecurity with a focus on IAM**, blending hands-on technical skills with security-first thinking. I will be posting my entire process here. You can follow more of my work here on GitHub. 
---

## 📚 Source / Attribution

This lab is based on official Microsoft Learn content and lab exercises. It was completed as part of my learning path toward specializing in **Identity and Access Management (IAM)** within cybersecurity.

### 🔗 Official References

- 📘 **Microsoft Learn Module**:  
  [Get started with identity and access management labs](https://learn.microsoft.com/en-us/training/modules/get-started-identity-access-labs/)  
  _This module introduces basic identity tasks using Microsoft Entra ID._

- 🧪 **Lab Instructions**:  
  [Lab 1 – Perform Basic User Management Tasks](https://microsoftlearning.github.io/Get-started-Microsoft-Entra-Management-Tasks/Instructions/Labs/01-perform-basic-user-management.html)  
  _This guided lab walks through user creation, license assignment, and role assignment._

- 📂 **Lab Files & CSV Templates**:  
  [MicrosoftLearning/SC-300 GitHub Repository – Lab 1 Files](https://github.com/MicrosoftLearning/SC-300-Identity-and-Access-Administrator/tree/master/Allfiles/Labs/Lab1)  
  _Official CSV files for bulk user import (Task 5) were sourced from this repository._

> ⚠️ **Disclaimer**: This repository is a personal educational project. It is not affiliated with or endorsed by Microsoft. All content is used under the terms of Microsoft’s publicly available training materials and GitHub repositories.

## 📌 Tags
`#MicrosoftEntra` `#AzureAD` `#IAM` `#CloudSecurity` `#SC300` `#AdminLabs` `#Cybersecurity`


