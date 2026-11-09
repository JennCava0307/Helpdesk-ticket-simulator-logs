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
  
---

### Ticket #NET17941602502962: Remote User VPN Disconnection & Stale DNS Resolution
* **User Issue:** Remote employee in Marketing lost VPN connection and could not reach corporate network resources or internal drives.
* **Environment:** Windows 11 / Remote (Work-From-Home) / Enterprise VPN Client
* **Impact:** High — Remote user completely cut off from internal business systems and file servers.
* **Diagnosis:** Identified stale local DNS cache on the client machine preventing the VPN client from re-establishing a secure tunnel to the gateway.
* **Action Taken:**
  * Initiated a secure Remote Desktop (RDP) session to connect directly to the user's remote workstation.
  * Launched terminal/command line interface as Administrator.
  * Executed `ipconfig /flushdns` to clear outdated/corrupted DNS entries.
  * Performed a controlled remote reboot of the workstation to re-initialize network adapters.
  * Guided the user through signing back into their desktop using their credentials.
  * Launched the enterprise VPN client and verified successful authentication and tunnel establishment.
* **Result:** Corporate VPN connected successfully, internal network reachability restored, and user verified full access to internal marketing resources. Issue resolved.
