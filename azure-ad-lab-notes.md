# Azure AD Lab Notes (Step-by-Step)

## Tenant Setup
- Created free Azure account and new Entra ID tenant: `olga-techlab.onmicrosoft.com`

## Users
- Added users: Borys (IT), Volodymyr (HR), Bohdan (Finance)
- Added custom attributes: department, location

## Groups
- Created groups: IT, HR, Finance
- Added users to corresponding groups

## Roles (RBAC)
- IT group → User Administrator  
- HR group → Password Administrator  

## Security
- Enabled MFA for IT group  
- Conditional Access: Require MFA outside the U.S.  

## Testing
- Logged in as each user and observed policies  

## Concepts Practiced
- MDM vs MAM (explored in Intune)  
- Autopilot workflow (dummy deployment profile)  
- Triage by impact & SLA (documented sample ticket prioritization)
