# Azure AD (Entra ID) Identity Lab Notes — Step-by-Step

## Tenant Setup
- Created a **free Azure account** and new **Entra ID tenant**: `olga-techlab.onmicrosoft.com`
- Verified tenant properties and license: *Microsoft Entra ID Free*
- Confirmed tenant overview shows: **5 users**, **1 group**, **0 applications**, **0 devices**

---

## Users
- Created test users:  
  - **Borys Johnsonuk** — IT  
  - **Volodymyr Zelenskua** — IT  
  - **Bohdan Khmelnytskua** — HR 
  - **Yaroslava Mahurchikh** — HR 
  - **Olga Zulkofske** — Global Administrator (default)
- Assigned **custom attributes**: *Department* and *Office location*
- Edited **Columns view** in *Users* list to display these custom attributes
- Verified all user accounts show “Member” type and “Enabled/Disabled” states

---

## Groups
- Created **IT-Support** security group
- Added **Borys Johnsonuk** as a group member
- Verified group membership from both *Group view → Members* and *User view → Groups* tabs
- Note: Group-based role assignment unavailable in *Free* license tier

---

## Roles (RBAC)
- Assigned **User Administrator** built-in directory role directly to user **Borys Johnsonuk**
- Verified under *Roles and administrators → User Administrator → Assignments*
- Demonstrates **user-level role-based access control (RBAC)** — giving limited administrative rights only to selected users
- Confirmed assignment visible under *User → Assigned roles*

---

## Security (MFA and Conditional Access)
- Enabled **per-user Multi-Factor Authentication (MFA)** for **Borys Johnsonuk** via the *Per-user MFA (classic)* portal
- Verified MFA **Status = Enabled**, **Enforced = No** (user has not yet completed registration)
- Observed that Conditional Access policies are **disabled in the Free tier**, but reviewed *Security → Conditional Access → Overview* to identify where MFA enforcement policies would normally be created

---

## Screenshots Captured
1️⃣ IT-Support group with member **Borys Johnsonuk**  
2️⃣ Role assignment showing **Borys** as **User Administrator**  
3️⃣ Per-user MFA status showing **Enabled**  
4️⃣ Users view showing **Department** and **Office Location**  
5️⃣ Conditional Access Overview (Free-tier restriction visible)

---

## Key Concepts Demonstrated
- **Tenant creation:** established a standalone Entra ID tenant and verified default settings  
- **User management:** created accounts, attributes, and visibility options  
- **Group creation:** organized users logically for role-based management  
- **RBAC:** delegated directory-level administrative rights to a single user (**Borys**)  
- **MFA setup:** configured and verified per-user MFA using legacy MFA portal  
- **Conditional Access (Free tier):** explored where policy creation is normally done  
- **Portal navigation:** identified exact paths for *Users, Groups, Roles,* and *MFA*  
- **Documentation discipline:** recorded each action and embedded matching screenshots in GitHub with clear file naming
