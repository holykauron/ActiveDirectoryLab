# Active Directory Home Lab

## Overview

This project documents the creation of a Windows Server 2022 Active Directory lab environment using VirtualBox.

The goal was to gain hands-on experience with:

- Active Directory Domain Services
- DNS Configuration
- Domain Controller Deployment
- Windows Client Domain Join
- User and Group Management
- Network Troubleshooting

## Lab Environment

### Virtualization Platform
- Oracle VirtualBox

### Server
- Windows Server 2022

### Client
- Windows 11

### Domain Name
- krantanlab.local

## Network Configuration

| Device | IP Address |
|----------|----------|
| Domain Controller | 192.168.50.10 |
| Windows 11 Client | 192.168.50.20 |

## Project Walkthrough

### Step 1: Install Windows Server 2022

Screenshot:

screenshots/server-installation.png

### Step 2: Configure Static IP

Configured:
- IP Address
- Subnet Mask
- Default Gateway
- Preferred DNS Server

static_ip.png

### Step 3: Install Active Directory Domain Services

Installed AD DS role through Server Manager.

windows_2022_installed.png

install_ad_ds.png

### Step 4: Promote Server to Domain Controller

Created:

krantanlab.local

screenshots/domain-controller.png

### Step 4: Create groups and Users for domain

user_creation_sucessful.png

### Step 5: Join Windows 11 to Domain

Successfully joined Windows 11 workstation to the domain.

client_joins_server_domain.png

### Step 6: Verify Connectivity

Used ping testing and DNS lookups.

connection_succesful.png

### Step 7: Sign into created user

Successfully signed into client as John Doe. 

switch_user.png

user_login_succesful.png

## Skills Demonstrated

- Windows Server Administration
- Active Directory
- DNS
- DHCP
- PowerShell
- Troubleshooting
- Domain Management
- Virtualization
- Networking

## Key Lessons Learned

- Importance of DNS in Active Directory
- Static IP configuration
- Domain Controller promotion process
- Domain user management
- Windows workstation integration
