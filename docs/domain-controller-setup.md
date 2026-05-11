# Domain Controller Setup

## Overview

This document describes the deployment and initial configuration of the primary Domain Controller used in the Active Directory lab environment.

The server was promoted to a Domain Controller to provide:
- centralized authentication,
- DNS services,
- identity management,
- Group Policy management.

---

## Environment

| Component | Value |
|---|---|
| Server Name | DC01 |
| Operating System | Windows Server 2025 |
| Domain Name | lab.local |
| Server Role | Domain Controller |
| Additional Services | DNS |

---

## Configuration Summary

The following configuration steps were completed:

1. Installed Active Directory Domain Services (AD DS)
2. Promoted the server to a Domain Controller
3. Created a new Active Directory forest and domain
4. Configured integrated DNS services
5. Configured static IP addressing for domain reliability
