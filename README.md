# Azure AD (Entra ID) Identity Mini-Lab

**Goal:** Build a small Azure AD (Entra ID) environment to practice identity management: users, groups, MFA, and Conditional Access.

---

## What I Did
- Created a new Entra ID tenant in the Azure portal  
- Added test users and security groups  
- Assigned role-based access (RBAC) directly to users 
- Enabled MFA for one group and tested sign-in  
- Built a Conditional Access policy requiring MFA outside the U.S.  
- Captured screenshots and notes

---

## Why It Matters
This lab demonstrates practical knowledge of identity and access management—skills used daily in IT support, systems administration, and technical engineering roles.

---

## Tools
Microsoft Entra ID (Azure AD) · Conditional Access · MFA (Microsoft Authenticator)

---

## Screenshots

**1️⃣ IT Support Group Members**
> Shows the IT-Support group in Azure AD with user Borys Johnsonuk assigned as a member.

![IT Support Group Members](https://github.com/olhazu-tech/azure-ad-identity-lab/blob/main/screenshots/azure_ad_identity_lab_screenshots_it_support_members.png)

---

**2️⃣ Borys User Administrator Role**
> Displays the role assignment screen where Borys Johnsonuk is assigned as a User Administrator.

![Borys User Administrator Role](https://github.com/olhazu-tech/azure-ad-identity-lab/blob/main/screenshots/azure_ad_identity_lab_screenshots_borys_user_admin_role.png)

---

**3️⃣ MFA Enabled for Borys Johnsonuk**  
> Shows per-user MFA enabled for Borys Johnsonuk in Microsoft Entra ID.
  
![Borys MFA Enabled](https://github.com/olhazu-tech/azure-ad-identity-lab/blob/main/screenshots/azure_ad_identity_lab_screenshots_borys_mfa_enabled.png)

---
## Key Concepts Learned
- MDM vs MAM: device vs app-level management  
- Autopilot workflow: vendor-registered hardware → Entra join → Intune setup  
- Triage by impact & SLA: prioritizing support tickets effectively

