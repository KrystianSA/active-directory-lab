# Deployment Steps

## Infrastructure Deployment

1. Created a dedicated resource group for the Active Directory lab environment

2. Deployed a Windows Server 2025 virtual machine to host the Active Directory infrastructure

3. Connected to the virtual machine remotely using RDP for administrative access

---

## Active Directory Configuration

4. Installed Active Directory Domain Services (AD DS) using Server Manager

5. Promoted the server to a Domain Controller and configured a new Active Directory forest and domain

6. Installed Group Policy Management Console (GPMC) using PowerShell

7. Created Organizational Units (OUs) using PowerShell to organize users and resources

8. Configured RBAC-oriented security groups for role-based access management

9. Created domain user accounts using PowerShell automation

---

## Group Policy & Security Configuration

10. Configured Group Policy Objects (GPOs) to enforce security settings including:

- minimum password length policy,
- machine inactivity timeout,
- removable storage access restrictions.

---

## Validation & Testing

11. Deployed an additional client virtual machine for validation testing

12. Verified domain communication and authentication functionality

13. Tested Group Policy deployment and enforcement on the client machine

14. Validated user account management operations including:
- password reset,
- account disablement,
- security group assignment.

15. Executed PowerShell scripts to identify inactive user accounts
