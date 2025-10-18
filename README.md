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

**3️⃣ MFA Configuration and Verification**
> Demonstrates enabling and verifying per-user MFA in Microsoft Entra ID (Azure AD).  
> The screenshot shows user **Borys Johnsonuk** listed with MFA status **Enabled**, confirming the setup worked and indicating where administrators can manage MFA options (enable, disable, or reset).

![Borys MFA Enabled](https://github.com/olhazu-tech/azure-ad-identity-lab/blob/main/screenshots/azure_ad_identity_lab_screenshots_borys_mfa_enabled.png)

---

**4️⃣ User Department and Location**  
> Shows the Azure AD Users view after adding custom attributes (Department and Office location) and editing Columns to display them.  

![User Department and Location](https://github.com/olhazu-tech/azure-ad-identity-lab/blob/main/screenshots/azure_ad_identity_lab_screenshots_user_department_location.png)

---

**5️⃣ Conditional Access Overview**

> Shows the Conditional Access Overview page in Microsoft Entra ID (Azure AD).  
> Policy creation options are disabled in the Free tier, but this screen demonstrates where administrators configure rules enforcing MFA and sign-in conditions.

![Conditional Access Overview](https://github.com/olhazu-tech/azure-ad-identity-lab/blob/main/screenshots/azure_ad_identity_lab_screenshots_conditional_access_overview.png)

---
## Key Concepts Learned

- **Tenant basics:** Created a new Microsoft Entra ID tenant and worked in the Entra admin center (Users, Groups, Roles & administrators).
- **User management:** Created user accounts with UPNs and initial passwords; saw “account enabled/disabled” and where to edit properties.
- **Groups vs. roles:** Built a **Security group** (IT-Support) and added a member; confirmed that group membership **does not** grant admin privileges by itself.
- **Directory roles (RBAC):** Assigned the **User Administrator** built-in role **directly to a user** (Borys Johnsonuk) and verified it under *Assigned roles*.
- **Licensing constraint:** Noted that assigning roles **to groups** requires Entra ID **P1/P2**; on Free tier only user assignments were possible.
- **Per-user MFA:** Enabled MFA for a user via **Per-user MFA** (classic portal) and verified the **Enabled** status.
- **Navigation know-how:** Learned exact portal paths for Users, Groups, Roles, and the Per-user MFA link; captured evidence screenshots.
- **Documentation workflow:** Organized a GitHub repo, added screenshots to `/screenshots/`, and embedded them inline in Markdown with clear captions.
- **Consistency discipline:** Aligned README/notes wording with real actions (roles assigned to **users**, not groups).


