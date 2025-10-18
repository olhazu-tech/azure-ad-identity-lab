# Azure AD (Entra ID) Identity Mini-Lab

### Goal
Build a small Microsoft Entra ID (Azure AD) environment to practice identity management: users, groups, roles, MFA, and Conditional Access.

---

## Step-by-Step: What I Did

1) **Created a new Microsoft Entra ID tenant**
   - Tenant name: **OlgaTechLab**
   - Primary domain: `olga-techlab.onmicrosoft.com`

2) **Created test users**
   - Borys Johnsonuk (IT)  
   - Bohdan Khmelnytskua (Finance)  
   - Volodymyr Zelenska (HR)  
   - Yaroslava Mahuchikh (HR)  
   - Olga Zulkofske (Global Admin)

3) **Created a security group**
   - Group name: **IT-Support**

4) **Added member to the group**
   - Added **Borys Johnsonuk** as a member of **IT-Support**

5) **Assigned directory role (RBAC) directly to a user**
   - Assigned **User Administrator** role to **Borys Johnsonuk**
   - Verified assignment under *User → Assigned roles*

6) **Enabled per-user MFA (classic portal)**
   - Enabled MFA for **Borys Johnsonuk**
   - Confirmed his MFA status shows **Enabled**
   - This step also served as verification (status review)

7) **Added custom user attributes**
   - Edited **Department** and **Office location** for each user
   - Customized Columns view in *Users* list to display them

8) **Reviewed Conditional Access overview**
   - Navigated to *Security → Conditional Access → Overview*
   - Verified that policy creation options are disabled under the Free tier
   - Documented where Conditional Access rules would be configured

9) **Documented everything in GitHub**
   - Added screenshots to `/screenshots/`
   - Embedded screenshots inline in Markdown
   - Wrote concise descriptions for each step

10) **Ensured documentation accuracy**
   - Updated README wording to reflect that roles were assigned **to users**, not groups
   - Verified consistency between portal screenshots and text

---

## Why It Matters
This lab demonstrates hands-on understanding of identity and access management—skills used daily in IT support, system administration, and technical engineering roles.

---

## Tools
**Microsoft Entra ID (Azure AD)** · **Conditional Access** · **MFA (Microsoft Authenticator)**

---

## Screenshots

**1️⃣ IT Support Group Members**  
> Shows the IT-Support group in Azure AD with user **Borys Johnsonuk** assigned as a member.  
![IT Support Group Members](https://github.com/olhazu-tech/azure-ad-identity-lab/blob/main/screenshots/azure_ad_identity_lab_screenshots_it_support_members.png)

---

**2️⃣ Borys User Administrator Role**  
> Displays the role assignment screen where **Borys Johnsonuk** is assigned as a **User Administrator**.  
![Borys User Administrator Role](https://github.com/olhazu-tech/azure-ad-identity-lab/blob/main/screenshots/azure_ad_identity_lab_screenshots_user_admin_role.png)

---

**3️⃣ MFA Configuration and Verification**  
> Demonstrates enabling and verifying per-user MFA in Microsoft Entra ID (Azure AD).  
> The screenshot shows **Borys Johnsonuk** listed with MFA status **Enabled**, confirming setup success and identifying where MFA options can be managed.  
![Borys MFA Enabled](https://github.com/olhazu-tech/azure-ad-identity-lab/blob/main/screenshots/azure_ad_identity_lab_screenshots_borys_mfa_enabled.png)

---

**4️⃣ User Department and Location**  
> Shows the Azure AD *Users* view after adding **Department** and **Office location** attributes and editing Columns to display them.  
![User Department and Location](https://github.com/olhazu-tech/azure-ad-identity-lab/blob/main/screenshots/azure_ad_identity_lab_screenshots_user_department_location.png)

---

**5️⃣ Conditional Access Overview**  
> Displays the Conditional Access Overview page in Microsoft Entra ID (Azure AD).  
> Policy creation is disabled in the Free tier, but this screen shows where administrators configure rules enforcing MFA and sign-in conditions.  
![Conditional Access Overview](https://github.com/olhazu-tech/azure-ad-identity-lab/blob/main/screenshots/azure_ad_identity_lab_screenshots_conditional_access_overview.png)

---

## Key Concepts Learned

- **Tenant setup** – Created a new Microsoft Entra ID tenant and worked in the Entra admin center.  
- **User management** – Created users with UPNs and passwords; reviewed account states and property editing.  
- **Groups vs. roles** – Created a Security group (IT-Support) and added members; confirmed groups alone don’t grant admin privileges.  
- **Directory roles (RBAC)** – Assigned the User Administrator built-in role directly to a user and verified assignment.  
- **Licensing constraint** – Noted that role-to-group assignment requires Entra ID P1/P2 (Free tier allows user-only).  
- **Per-user MFA** – Enabled and confirmed MFA for one user using the classic portal.  
- **Custom attributes** – Added Department and Office Location fields and displayed them in user list.  
- **Conditional Access overview** – Located where MFA and sign-in rules would be configured (Free tier limitations).  
- **Portal navigation** – Practiced moving through Users, Groups, Roles, MFA, and Security sections.  
- **Documentation discipline** – Created a GitHub repo, uploaded screenshots, and embedded Markdown links clearly tied to each step.

---

📘 *Author: Olga Zulkofske*  
🗓️ *Completed: October 2025*
