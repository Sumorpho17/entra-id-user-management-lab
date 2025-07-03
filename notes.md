# 📝 Lab Notes – Microsoft Entra ID User Management

## Lab Context
Hands-on experience with basic identity and access management tasks using Microsoft Entra ID.

---

## 🚧 Challenges Faced

### ❌ Task 2 - Assign License
- **Issue**: Couldn't assign the Power Automate Free license.
- **Reason**: My account didn’t have access to the Microsoft 365 Admin Center.
- **Fix**: Will request global admin or license management permissions before future attempts.
- **Lesson**: Licensing is managed through the M365 admin portal, not just Entra.

---

### ⚠️ Task 5 - Bulk Import Users
- **Issue**: Users failed to import.
- **Cause**: I didn't update the domain name in the CSV to match my tenant (e.g., `@mydomain.onmicrosoft.com`).
- **Fix**: Replaced placeholder domain in the CSV with actual tenant domain before upload.
- **Light Bulb Moment**: Organizational users must use the tenant’s domain, or they’ll fail import or be treated as guests.

---

## 💡 Key Insights

- Role assignment types (Eligible vs Active) are part of **PIM (Privileged Identity Management)**.
- Guest users are easy to onboard but **limited in permission scope**.
- CSV files must follow precise formatting for bulk user operations.
- Always back up auto-generated passwords when creating new users manually.

---

## 🔄 What I’d Do Differently Next Time
- Validate CSV with Entra format checker before import.
- Confirm permissions on admin accounts before starting.
- Test guest invites and role assignment across multiple browsers for user simulation.

---

## 🧰 Useful Links

- Microsoft Entra Admin Center: [https://entra.microsoft.com](https://entra.microsoft.com)
- Microsoft 365 Admin Center: [https://admin.microsoft.com](https://admin.microsoft.com)
- PIM Documentation: [https://learn.microsoft.com/en-us/azure/active-directory/privileged-identity-management](https://learn.microsoft.com/en-us/azure/active-directory/privileged-identity-management)

