# Active Directory Home Lab

---

## Loom Walkthrough

[🎥 Watch Full Lab Demonstration](YOUR_LOOM_LINK)

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

---

## Objectives

- Build a functional Active Directory domain environment
- Configure a Domain Controller
- Configure DNS and DHCP services
- Join Windows clients to the domain
- Create and manage users, groups, and OUs
- Apply Group Policy Objects (GPOs)
- Understand authentication and centralized identity management
- Practice troubleshooting and administrative workflows

---

## Architecture

![Lab Architecture](./media/diagrams/ad-lab-diagram.png)

### Environment

| Machine | Role | Operating System |
|---|---|---|
| DC01 | Domain Controller / DNS / DHCP | Windows Server 2019 |
| CLIENT01 | Domain Joined Workstation | Windows 10 |
| HOST | Virtualization Host | VirtualBox |

---

## Technologies Used

- Active Directory Domain Services (AD DS)
- Windows Server 2019
- Windows 10
- DNS
- DHCP
- Group Policy Management
- Oracle VirtualBox
- PowerShell

---

## Security Concepts

- Least Privilege
- Centralized Authentication
- Organizational Unit Segmentation
- Group Policy Enforcement
- Password Policies
- Identity Management
- Administrative Access Control

---

## Screenshots

### Active Directory Users and Computers

![ADUC](./media/screenshots/aduc.png)

### Group Policy Management

![GPO](./media/screenshots/gpo.png)

### Domain Joined Client

![CLIENT](./media/screenshots/client-domain.png)

---

## Validation

The environment was validated by:

- Successful domain deployment
- DNS resolution between systems
- DHCP address assignment
- Successful domain join
- User authentication testing
- GPO application testing

---

## Lessons Learned

- Importance of DNS in Active Directory environments
- Common networking issues during domain join
- Group Policy inheritance behavior
- Administrative workflow inside Windows domains
- Benefits of centralized identity management

---
