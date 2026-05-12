# Microsoft Entra ID (Azure AD) - Identity & Security Lab

## 🎯 Project Overview
This project simulates a corporate IT environment using **Microsoft Entra ID**. It demonstrates the implementation of modern identity management and security protocols (Zero Trust) required for a Helpdesk/Technical Support role.

## 🛠️ Implementation Steps

### 1. User & Group Lifecycle Management
*   **User Provisioning:** Created standardized user accounts (e.g., John Smith) with "Change password at next logon" enforced.
*   **Security Groups:** Implemented a departmental group structure (`Sales-Department`) to streamline access control.

### 2. Security & Efficiency (SSPR)
*   **Self-Service Password Reset:** Configured **SSPR** for specific departments to reduce Helpdesk ticket volume and improve user autonomy.
*   **Authentication Methods:** Enabled Email and SMS-based verification for secure password recovery.

### 3. Advanced Security (Conditional Access & MFA)
*   **Zero Trust Implementation:** Created a **Conditional Access Policy** to enforce **Multi-Factor Authentication (MFA)** for all cloud applications.
*   **Security Defaults:** Transitioned from basic security defaults to granular, policy-based access control.

## 📊 Business Impact
*   **Reduced Overhead:** SSPR implementation can reduce password-related tickets by up to 30%.
*   **Enhanced Security:** Mandatory MFA mitigates the risk of compromised credentials by 99.9%.

## 📸 Lab Documentation

### 1. Microsoft 365 Admin Center Overview
<img width="1914" height="907" alt="Main screen" src="https://github.com/user-attachments/assets/f5681ceb-eb13-45c7-892d-92bea9998ee4" />
*Initial setup of the Teo Labs IT tenant, showing the central administration dashboard for Microsoft 365 services.*

---

### 2. User Provisioning & Identity Management
<img width="1915" height="908" alt="users" src="https://github.com/user-attachments/assets/eda8273a-fd3d-4609-940f-0387351e1e60" />
*Demonstrating the creation of a standard corporate user (John Smith). This shows proficiency in managing user lifecycles and identity within Entra ID.*

---

### 3. Security Group Management & Identity Governance
<img width="1912" height="907" alt="groups" src="https://github.com/user-attachments/assets/b62ed8b5-e3ca-4a41-8cbd-a8cd0d6fe5d6" />
*Configured Department-based Security Groups to manage access at scale. This screenshot demonstrates the 'Sales-Department' group with John Smith assigned as a member, ensuring efficient Role-Based Access Control (RBAC).*

---

### 4. Authentication Method Policies (MFA)
<img width="1915" height="868" alt="auth methods" src="https://github.com/user-attachments/assets/bb0111f6-03bb-4d8e-841a-cbfa0a409650" />
*Defining global authentication methods for the organization. This shows the enablement of Microsoft Authenticator, SMS, and Email OTP, providing a secure and flexible Multi-Factor Authentication (MFA) experience for end-users.*

---

### 5. Conditional Access Implementation (Zero Trust)
<img width="1917" height="913" alt="Policy" src="https://github.com/user-attachments/assets/3967a40b-a246-469c-b23e-68cd0824e181" />
*Finalized the deployment of a Conditional Access policy titled 'Enforce MFA for Sales Department'. This demonstrates a Zero Trust security approach, ensuring that specific groups must pass Multi-Factor Authentication challenges before accessing corporate cloud resources.*













