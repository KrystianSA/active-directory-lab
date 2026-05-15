# Active Directory Home Lab

<img width="1470" height="835" alt="Zrzut ekranu 2026-05-15 o 19 37 45" src="https://github.com/user-attachments/assets/e350eb89-384f-4f75-b10d-8e6125d76948" />

- [Overview](#Overview)
- [The Business Problem This Lab Solves](#The-Business-Problem-This-Lab-Solves)
- [Technologies Used](#Technologies-Used)
- [Security Concepts](#Security-Concepts) 

## Why This Lab Matters

Active Directory remains a core identity system in enterprise environments, responsible for authentication, authorization, and policy management.

This lab simulates a small corporate Windows domain environment and focuses on real-world administration concepts such as DNS, DHCP, Group Policy, and centralized identity management.

The knowledge gained here directly applies to hybrid and cloud environments like Microsoft Entra ID (Azure AD).

---

## Video Walkthrough

[Reset Password](https://drive.google.com/file/d/1Nlw4dm7aM0poAroqg-sbQqOb3GVHnVcH/view?usp=share_link)
[Adding User](https://drive.google.com/file/d/1InjiWfsjNdIBpGe7ROhh9gl2V-M2qHgl/view?usp=share_link)
[Disable User Account](https://drive.google.com/file/d/1tQCAiMZo1-xLkFjtu--5hlGn2pAjDQEd/view?usp=share_link)
[GPO Policy](https://drive.google.com/file/d/12l1R88v9I_X9fS9v4Zpv_u8JJMw3fCnP/view?usp=share_link)

---

## Overview

This project demonstrates the deployment and configuration of a Windows-based Active Directory environment inside a virtualized lab.

The lab was created to gain hands-on experience with:

- Active Directory Domain Services (AD DS)
- DNS & DHCP configuration
- Domain administration
- Group Policy management
- User and organizational unit management
- Windows client domain joining
- Basic identity and access management concepts

The environment simulates a small enterprise infrastructure and focuses on administration, networking, and security fundamentals commonly used in production environments.

## The Business Problem This Lab Solves

Every organisation that runs Windows infrastructure — and the majority of enterprises do — relies on Active Directory to answer one fundamental question: who is allowed to do what?
Active Directory is the identity backbone. It controls which users can log into which computers, which groups can access which file shares, and which policies apply to which parts of the organisation.
When a new employee joins, IT creates their account in Active Directory and adds them to the right groups. Their access to email, shared drives, printers, and applications is granted automatically based on group membership. When they leave, IT disables one account and every door closes simultaneously.
This is not legacy technology. Hybrid environments use Active Directory on-premises and sync identities to Microsoft Entra ID (formerly Azure AD) in the cloud. Understanding how to build and manage an Active Directory environment is foundational knowledge that applies directly to cloud roles.

## Technologies Used

- Active Directory Domain Services (AD DS)
- Windows Server 2025
- Azure Portal
  - Virtual Machine
  - Resource group
---

## Security Concepts

- Least Privilege
- Centralized Authentication
- Organizational Unit Segmentation
- Group Policy Enforcement
- Password Policies
- Identity Management
- Administrative Access Control
