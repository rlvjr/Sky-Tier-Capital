<div align="center">

# Server Build

## Windows Server 2022 Deployment

</div>

---

## Overview

This document outlines the deployment and initial configuration of the Sky Tier Capital Windows Server 2022 infrastructure environment.

The server was created as the foundation for the enterprise lab environment and provides the platform for Active Directory Domain Services, DNS, and Group Policy management.

---

## Server Configuration

| Component | Configuration |
|:---:|:---:|
| Operating System | Windows Server 2022 Standard Evaluation |
| Virtualization Platform | Oracle VirtualBox |
| Server Purpose | Domain Infrastructure Server |
| Domain Environment | SkyTierCapital.local |
| Server Role | Domain Controller |

---

## Virtual Machine Deployment

The Windows Server environment was deployed using Oracle VirtualBox to simulate an enterprise server infrastructure.

Initial deployment tasks included:

- Creating the virtual machine
- Allocating system resources
- Installing Windows Server 2022
- Completing initial operating system configuration
- Preparing the server for infrastructure roles

---

## Initial Server Configuration

The following configuration tasks were completed after installation:

- Configured administrator access
- Verified operating system functionality
- Configured server networking requirements
- Installed required Windows Server roles and features
- Prepared the server for Active Directory deployment

---

## Installed Server Roles

The following roles and features were installed:

### Active Directory Domain Services (AD DS)

Provides centralized identity and access management capabilities.

Used for:

- User authentication
- Domain management
- Security group administration
- Computer account management

---

### DNS Server

Provides internal name resolution required for Active Directory functionality.

Used for:

- Domain name resolution
- Service discovery
- Communication between domain resources

---

### Group Policy Management

Provides centralized configuration management for domain-connected systems.

Used for:

- Security configuration
- User restrictions
- System policies
- Administrative control

---

### Remote Server Administration Tools (RSAT)

Provides administrative tools for managing Windows Server services and infrastructure components.

---

## Deployment Challenges

During the server deployment process, troubleshooting was required for:

- Virtual machine resource limitations
- Storage constraints
- Windows Server installation configuration
- VirtualBox environment adjustments

These challenges provided practical experience troubleshooting virtualization and server deployment issues.

---

## Current Status

Completed:

- Windows Server 2022 deployment
- Server configuration
- Required infrastructure role installation
- Domain Controller promotion
- Initial domain setup

Future configuration:

- Create Organizational Units
- Configure user accounts
- Implement security groups
- Configure Group Policy Objects
- Add domain-connected client systems
- Expand security documentation

---

## Screenshots

Documentation evidence will be added as configuration milestones are completed.

Planned screenshots:

- Virtual machine configuration
- Windows Server installation
- Server Manager roles
- Active Directory configuration
- Domain Controller settings
