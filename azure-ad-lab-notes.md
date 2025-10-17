# Azure AD Lab Notes (Step-by-Step)

## Tenant Setup
- Created a free Azure account and new Entra ID tenant: **olga-techlab.onmicrosoft.com**

## Users
- Added users: **Borys Johnsonuk (IT)**, **Volodymyr Zelenskua (HR)**, **Bohdan Khmelnytskua (Finance)**, **Yaroslava Mahurchikh (Intern)**
- Assigned custom attributes: **department**, **location**

## Groups
- Created groups: **IT-Support**, **HR**, **Finance**
- Added corresponding users to each group

## Roles (RBAC)

- Assigned **User Administrator** role directly to user *Borys Johnsonuk*.

> Demonstrates user-level role-based access control (RBAC) assignment in Microsoft Entra ID.



## Security
- Enabled MFA the user of IT-Support group (not the whole group as Zure free version limited this feature)
- Tested sign-in and Conditional Access policy
