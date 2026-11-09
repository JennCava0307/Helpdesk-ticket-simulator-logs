# Tier 1 Helpdesk & Service Desk Ticket Resolution Portfolio

## 📌 Project Overview
This repository serves as a practical, hands-on portfolio of entry-level IT Support and Service Desk ticket resolutions. Scenarios were completed using enterprise simulation labs, focusing on Tier 1 user support, Active Directory administration, network diagnostics, and ITSM ticketing workflows.

---

### Ticket #INC0012853: New Hire User Provisioning & Group Assignment
* **User Issue:** HR submitted a onboarding request for a new employee needing computer access, email setup, and security group permissions.
* **Environment:** Windows Server / Active Directory Users & Computers (ADUC) / Microsoft 365
* **Diagnosis:** Identified required department, manager, and role-based permissions based on the onboarding ticket request.
* **Action Taken:**
  * Created a new user object in the appropriate Organizational Unit (OU) with standard naming conventions (`First.Last`).
  * Configured user account details including display name, username, and primary SMTP email address.
  * Added the new user to three required Active Directory groups (Department Group, Shared Storage Access Group, and Distribution List).
* **Result:** User account successfully provisioned and verified in Active Directory. Ticket resolved.
