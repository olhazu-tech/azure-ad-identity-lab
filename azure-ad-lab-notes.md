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
- **IT-Support group → User Administrator**
- **HR group → Password Administrator**

## Security
- Enabled MFA for IT-Support group
- Tested sign-in and Conditional Access policy
