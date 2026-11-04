# Enterprise IT Infrastructure Homelab

### Windows Server 2025 | Active Directory | Hyper-V | Windows 11 | Ubuntu Linux

## Project Overview

Designed and deployed a simulated corporate IT environment using Microsoft Hyper-V to develop hands-on experience in enterprise IT support and systems administration.

The environment consists of five virtual machines connected through an isolated corporate network (`corp.test`).

## Technologies Used

- Windows Server 2025
- Active Directory Domain Services
- DNS and DHCP
- Group Policy Management
- Windows 11 and RSAT
- SMB File Sharing and NTFS Permissions
- PowerShell and WinRM
- Ubuntu Server and OpenSSH
- UFW Firewall

## Network Architecture

![Corporate IT Homelab Architecture](diagrams/network-architecture.svg)

## Infrastructure

| Machine | Role |
|---|---|
| DC-01 | Domain Controller, DNS, DHCP, Group Policy |
| FS-01 | Windows File Server |
| CLIENT-01 | Employee Workstation |
| IT-ADMIN-01 | IT Administration Workstation |
| LINUX-01 | Ubuntu Server and SSH |

## Skills Demonstrated

- Created Active Directory organizational units, user accounts, and security groups.
- Configured DNS, DHCP, and Group Policy.
- Implemented delegated password-reset permissions for IT administration.
- Migrated an SMB share to a dedicated Windows file server.
- Configured NTFS permissions to restrict departmental access.
- Installed RSAT for remote server administration.
- Managed a Windows server through PowerShell Remoting.
- Deployed an Ubuntu server with a static IP address.
- Configured SSH connectivity and Linux firewall rules.

## Project Screenshots

### Hyper-V Virtual Infrastructure
![Hyper-V](screenshots/01-hyperv-infrastructure.png)

### Active Directory
![Active Directory](screenshots/02-active-directory-structure.png)

### Group Policy
![Group Policy](screenshots/03-group-policy-management.png)

### File Server
![SMB Share](screenshots/04-file-server-smb-shares.png)

### PowerShell Remoting
![PowerShell Remoting](screenshots/05-powershell-remoting.png)

### Linux SSH Administration
![Linux SSH](screenshots/06-linux-ssh-administration.png)

## Environment

This is an independently built, isolated educational lab designed for hands-on IT administration, troubleshooting, and skills development.
