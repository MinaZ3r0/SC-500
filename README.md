# SC-500
Microsoft Certified: Cloud and AI Security Engineer Associate

This certification validates your ability to design, implement, and manage end‑to‑end security controls across Azure, hybrid, and AI-enabled environments to protect identities, data, applications, infrastructure, and maintain regulatory compliance.

> [!TIP]
> In some old documentation in the web they may refer Entra ID formally known as Azure AD.
> Similarly the SC-500 is also known as AZ-500. 

https://learn.microsoft.com/en-us/credentials/certifications/cloud-and-ai-security-engineer-associate/?practice-assessment-type=certification

# Introduction
These are my self notes when learning through.

Please note this not the official guide, please refer to MS learn for official learning material as information changes over time with technology.

# Secure access to resources by using MS Entra ID

## PIM
Privileged Identity Management (PIM) - allows you to manage, control and monitor access to resources in your organsiation.

> [!TIP]
> Always follow the least access, enough to complete their role. The user only needs to elevate for a x period of time before the access is removed.
> You might even require an approval by someone first before allowing to elevate to the role to complete x task.

Licensing required for PIM (You need one of these two.) :
- MS Entra ID P2
- MS Entra ID Governance

> [!TIP]
> Sometimes these licenses are bundled in other packages that you might already own like in MS E5 which is already bundled in the subscription.

Key features of PIM:
- JIT (just-in-time) access to Entra ID and Azure resources.
- Time-bound access to resources using start and end dates.
- Enforce approval to activate privileged roles.
- Enforce Multi-factor authentication to activate a role.
- Justification to understand to activate a role.
- Receive notifications when privileged roles are activated.
- Conduct access reviews to ensure users still need roles.
- Download audit history for internal or external audit.

<img width="978" height="485" alt="{D10E5B57-6A9F-43C0-9F71-7A8C92F54A12}" src="https://github.com/user-attachments/assets/6be64ecc-d3a6-4275-8303-47f6e1123ddb" />

These are the only two roles that can grant access to other administrators.
> [!Note]
> - Privileged role administrator
> - Global Administrator

The Global Administrator, Security Administrator, Global Reader and Security Reader can also view assignments to roles in Privileged Identity Management.

## Implementation of PIM
MS Entra ID > Privileged Identity Management > MS Entra roles
Roles -
Within here you can click on a specific role or add a new assignment

<img width="978" height="476" alt="{491C6476-A790-4F70-AF13-04CC439BB66E}" src="https://github.com/user-attachments/assets/9a5b1b69-ae1b-49ac-9ffd-089b432abb59" />


