# Windows Server & Active Directory Fundamentals

## What is Windows Server?

Windows Server is a server operating system developed by Microsoft.

Unlike Windows 10 or Windows 11, which are designed for end users, Windows Server is designed to:

* Manage users
* Manage computers
* Host applications
* Provide network services
* Manage security policies
* Control organizational IT infrastructure

---

# Common Windows Server Versions

| Version             | Release Year |
| ------------------- | ------------ |
| Windows Server 2012 | 2012         |
| Windows Server 2016 | 2016         |
| Windows Server 2019 | 2018         |
| Windows Server 2022 | 2021         |

---

# Why Organizations Use Windows Server?

Organizations use Windows Server for:

* Centralized User Management
* File Sharing
* Printer Sharing
* Authentication
* Security Policies
* Application Hosting

Example:

Instead of creating user accounts separately on 500 computers, an administrator can manage everything from a single server.

---

# What is a Server?

A server is a computer that provides services to other computers.

Examples:

### File Server

Stores and shares files.

### Print Server

Manages printers.

### Web Server

Hosts websites.

### Database Server

Hosts databases.

### Mail Server

Handles email services.

---

# Client-Server Architecture

In a network:

### Client

Requests services.

Examples:

* Laptop
* Desktop
* Mobile Phone

### Server

Provides services.

Example:

```text
Client → Request
Server → Response
```

---

# What is Active Directory (AD)?

Active Directory is Microsoft's directory service.

It stores information about:

* Users
* Computers
* Groups
* Printers
* Policies
* Resources

Think of Active Directory as a giant organizational database.

---

# Why Active Directory?

Without AD:

* Each computer has separate accounts.
* Management becomes difficult.

With AD:

* Centralized Management
* Centralized Authentication
* Better Security

---

# Real-Life Example

Suppose a company has:

* 1000 Employees
* 500 Computers

Without Active Directory:

Administrator manages accounts individually.

With Active Directory:

Everything is managed from one central location.

---

# What is a Domain?

A Domain is a logical group of computers and users managed by Active Directory.

Example:

```text
company.com
```

All users and computers belong to this domain.

---

# Benefits of Domains

* Centralized Authentication
* Centralized Security
* Easier Administration

---

# What is a Domain Controller (DC)?

A Domain Controller is a server running Active Directory services.

Responsibilities:

* User Authentication
* Authorization
* Group Policy Management
* Directory Services

Think:

```text
Domain Controller
       ↓
Controls Domain
```

---

# What is Authentication?

Authentication verifies identity.

Question:

```text
Who are you?
```

Example:

User enters:

* Username
* Password

AD verifies credentials.

---

# What is Authorization?

Authorization determines permissions.

Question:

```text
What can you access?
```

Example:

Employee:

* Can access HR Portal

Cannot:

* Modify Server Settings

---

# Active Directory Objects

Everything stored in AD is called an Object.

Examples:

* Users
* Computers
* Groups
* Printers

---

# User Account

Represents an employee.

Example:

```text
priyasha@company.com
```

Used for:

* Login
* Email
* Resource Access

---

# Computer Account

Represents a computer joined to the domain.

Example:

```text
PC-001
```

---

# Group

Collection of users.

Purpose:

Simplify permission management.

Example:

```text
HR Team
```

Instead of assigning permissions to 50 users individually, assign permissions to the group.

---

# Organizational Unit (OU)

OU = Organizational Unit

Used to organize Active Directory objects.

Example:

```text
Company
 ├─ HR
 ├─ Finance
 ├─ IT
 └─ Sales
```

Benefits:

* Easier Administration
* Better Policy Management

---

# What is DNS?

DNS = Domain Name System

Converts:

```text
company.com
```

into

```text
192.168.1.10
```

Active Directory heavily depends on DNS.

---

# What Happens During Login?

Step 1:

User enters:

```text
Username
Password
```

Step 2:

Computer contacts Domain Controller.

Step 3:

Credentials are verified.

Step 4:

Access granted.

---

# Advantages of Active Directory

### Centralized Management

Manage everything from one place.

---

### Single Sign-On (SSO)

One login for multiple resources.

---

### Better Security

Centralized policies and access control.

---

### Scalability

Supports thousands of users and computers.

---

# Common Active Directory Terms

| Term | Meaning             |
| ---- | ------------------- |
| AD   | Active Directory    |
| DC   | Domain Controller   |
| OU   | Organizational Unit |
| DNS  | Domain Name System  |
| SSO  | Single Sign-On      |

---

# Quick Revision

## Active Directory Stores

* Users
* Computers
* Groups
* Printers
* Policies

---

## Domain Controller Responsibilities

* Authentication
* Authorization
* Group Policies

---

## Authentication

Who are you?

---

## Authorization

What can you access?

---

## Organizational Unit

Logical container used to organize AD objects.

---

## Domain

Logical collection of users and computers.

---

# Most Asked TCS ITIS Questions

### What is Active Directory?

Microsoft's directory service for managing users, computers, and resources.

---

### What is a Domain Controller?

A server running Active Directory services.

---

### What is a Domain?

A logical collection of users and computers.

---

### What is an OU?

Organizational Unit used to organize AD objects.

---

### What is the difference between Authentication and Authorization?

Authentication verifies identity; Authorization determines permissions.

---

### Why is DNS important for Active Directory?

AD uses DNS to locate domain controllers and services.

---

### What are Active Directory Objects?

Users, Computers, Groups, Printers, etc.


# Group Policy (GPO), User Management & Permissions

## What is Group Policy?

Group Policy is a feature in Windows Server that allows administrators to centrally manage and configure users and computers within a domain.

Instead of configuring settings individually on hundreds of computers, administrators can apply policies from a central location.

Example:

```text id="gpo1"
Administrator
      ↓
Group Policy
      ↓
1000 Computers
```

---

# Why Use Group Policy?

Benefits:

* Centralized Management
* Improved Security
* Standardized Configuration
* Reduced Administrative Effort

---

# What is a Group Policy Object (GPO)?

A GPO is a collection of settings that can be applied to:

* Users
* Computers

Examples:

* Password Policies
* Desktop Restrictions
* Software Installation
* Security Settings

---

# Types of Group Policies

## Computer Configuration

Applied when the computer starts.

Affects:

* Computer settings
* Security settings
* Startup scripts

Example:

Disable USB devices on all company computers.

---

## User Configuration

Applied when a user logs in.

Affects:

* Desktop settings
* Start Menu
* Control Panel access

Example:

Prevent users from changing wallpapers.

---

# Password Policy

One of the most common security policies.

Used to enforce:

* Password Length
* Password Complexity
* Password Expiration

---

# Common Password Policy Settings

### Minimum Password Length

Example:

```text id="pp1"
Minimum Length = 8 Characters
```

---

### Password Complexity

Password must contain:

* Uppercase Letter
* Lowercase Letter
* Number
* Special Character

Example:

```text id="pp2"
Welcome@123
```

---

### Password Expiration

Users must change passwords after a specified period.

Example:

```text id="pp3"
90 Days
```

---

# Account Lockout Policy

Protects against brute-force attacks.

Example:

```text id="al1"
5 Failed Login Attempts
      ↓
Account Locked
```

Benefits:

* Improved Security
* Prevents Unauthorized Access

---

# User Account Management

Administrators create and manage user accounts in Active Directory.

User Account Stores:

* Username
* Password
* Contact Information
* Department Details

---

# Common User Management Tasks

### Create User

Example:

```text id="um1"
John Smith
john.smith@company.com
```

---

### Reset Password

Used when users forget passwords.

---

### Disable Account

Used when:

* Employee leaves organization
* Security concerns arise

---

### Delete Account

Removes user permanently.

---

# Group Management

Groups simplify permission assignment.

Instead of assigning permissions individually, permissions are assigned to groups.

---

# Example

Without Groups:

```text id="gm1"
User1
User2
User3
User4
```

Assign permissions individually.

---

With Groups:

```text id="gm2"
HR Group
     ↓
Users
```

Assign permissions once to the group.

---

# Types of Groups

## Security Groups

Used for:

* Access Control
* Permission Assignment

Example:

```text id="sg1"
Finance Team
```

Can access finance files.

---

## Distribution Groups

Used for:

* Email Distribution

Example:

```text id="sg2"
all-employees@company.com
```

Not used for security permissions.

---

# File Permissions

Windows controls file access through permissions.

Users can be granted:

* Read
* Write
* Modify
* Full Control

---

# NTFS Permissions

NTFS permissions are applied to files and folders stored on NTFS file systems.

---

## Read

User can:

* Open Files
* View Content

Cannot modify.

---

## Write

User can:

* Create Files
* Edit Files

---

## Modify

User can:

* Read
* Write
* Delete

---

## Full Control

User can:

* Read
* Write
* Modify
* Change Permissions

Highest permission level.

---

# NTFS Permission Hierarchy

```text id="ntfs1"
Full Control
     ↓
Modify
     ↓
Read & Execute
     ↓
Read
```

---

# Share Permissions

Applied when folders are shared over a network.

Common Permissions:

* Read
* Change
* Full Control

---

# NTFS vs Share Permissions

| NTFS Permissions          | Share Permissions   |
| ------------------------- | ------------------- |
| Applied Locally & Network | Network Access Only |
| More Granular             | Simpler             |
| File System Based         | Share Based         |

---

# Effective Permissions

When both NTFS and Share Permissions exist:

Most Restrictive Permission Wins.

Example:

```text id="ep1"
Share Permission = Full Control
NTFS Permission = Read
```

Effective Permission:

```text id="ep2"
Read
```

---

# Principle of Least Privilege

Very important security concept.

Users should receive only the permissions required to perform their job.

Example:

HR employee should not have:

* Server Admin Rights
* Database Admin Rights

Benefits:

* Better Security
* Reduced Risk

---

# Security Best Practices

### Use Strong Passwords

Example:

```text id="sb1"
Tcs@2026Secure
```

---

### Enable Account Lockout

Protects against brute-force attacks.

---

### Use Security Groups

Avoid assigning permissions directly to users.

---

### Follow Least Privilege

Grant minimum required access.

---

### Disable Unused Accounts

Reduces security risks.

---

# Quick Revision

## GPO

Centralized configuration management.

---

## Password Policy

* Length
* Complexity
* Expiration

---

## Account Lockout

Locks account after multiple failed login attempts.

---

## Security Group

Used for permissions.

---

## Distribution Group

Used for emails.

---

## NTFS Permissions

* Read
* Write
* Modify
* Full Control

---

## Least Privilege

Give only required permissions.

---

# Most Asked TCS ITIS Questions

### What is a GPO?

A collection of settings applied to users and computers.

---

### What is the purpose of Group Policy?

Centralized management and configuration.

---

### What is an Account Lockout Policy?

Locks accounts after multiple failed login attempts.

---

### What is the difference between Security Groups and Distribution Groups?

Security Groups are used for permissions; Distribution Groups are used for email distribution.

---

### What are NTFS Permissions?

Permissions controlling access to files and folders.

---

### Which permission is highest?

Full Control.

---

### What is the Principle of Least Privilege?

Users should receive only the permissions required to perform their job.

---

### When NTFS and Share permissions conflict, which permission applies?

The most restrictive permission.

# Windows Server Roles, DHCP, DNS, File Server & Print Server

## What are Server Roles?

A Server Role is a primary function that a Windows Server performs.

Think of a role as a specific job assigned to the server.

Example:

```text
Server
  ↓
DNS Server
```

The server's job is to resolve domain names.

---

# Roles vs Features

Many beginners confuse these terms.

## Server Role

Provides a major network service.

Examples:

* DNS Server
* DHCP Server
* Active Directory
* File Server

---

## Feature

Provides additional functionality.

Examples:

* Windows Backup
* BitLocker
* Failover Clustering

---

# Server Manager

Server Manager is the central management console in Windows Server.

Administrators use it to:

* Add Roles
* Remove Roles
* Manage Servers
* Monitor Services

---

# Common Windows Server Roles

### Active Directory Domain Services (AD DS)

Provides:

* Authentication
* Authorization
* User Management
* Domain Management

Creates Domain Controllers.

---

### DNS Server

Provides Domain Name Resolution.

Converts:

```text
www.company.com
```

into

```text
192.168.1.10
```

Without DNS:

Users would need to remember IP addresses.

---

# Why DNS is Important?

Active Directory depends heavily on DNS.

Domain Controllers register themselves in DNS.

Clients use DNS to locate:

* Domain Controllers
* Servers
* Services

---

# DNS Components

## DNS Record

Stores information inside DNS.

Common records include:

### A Record

Maps:

```text
Hostname → IPv4 Address
```

Example:

```text
server.company.com
→
192.168.1.100
```

---

### AAAA Record

Maps:

```text
Hostname → IPv6 Address
```

---

### CNAME Record

Alias for another hostname.

Example:

```text
mail.company.com
↓
server.company.com
```

---

### MX Record

Mail Exchange Record.

Used for:

* Email Routing

---

# What is DHCP?

DHCP stands for:

```text
Dynamic Host Configuration Protocol
```

Purpose:

Automatically assigns IP addresses to devices.

---

# Why DHCP?

Without DHCP:

Administrators manually configure:

* IP Address
* Subnet Mask
* Gateway
* DNS

For every device.

With DHCP:

Everything is assigned automatically.

---

# Example

Without DHCP:

```text
PC1
IP: 192.168.1.10

PC2
IP: 192.168.1.11

PC3
IP: 192.168.1.12
```

Configured manually.

---

With DHCP:

```text
DHCP Server
      ↓
Automatically Assigns IPs
```

---

# DHCP Process

Important Interview Topic

Known as:

```text
DORA Process
```

---

## D - Discover

Client searches for DHCP server.

---

## O - Offer

DHCP server offers an IP address.

---

## R - Request

Client requests offered IP.

---

## A - Acknowledge

Server confirms assignment.

---

# DHCP Scope

A Scope is a range of IP addresses that DHCP can assign.

Example:

```text
192.168.1.100
to
192.168.1.200
```

---

# DHCP Reservation

Assigns a fixed IP address to a specific device.

Uses:

* MAC Address
* Permanent Assignment

Example:

Printer always receives:

```text
192.168.1.50
```

---

# What is a File Server?

A File Server stores and shares files across a network.

Benefits:

* Centralized Storage
* Easier Backup
* Access Control

---

# File Sharing Example

```text
File Server
      ↓
Shared Folder
      ↓
Employees Access Files
```

---

# Advantages of File Servers

* Centralized Data
* Improved Security
* Easier Management
* Backup Support

---

# Shared Folder

Folder accessible over a network.

Example:

```text
\\FileServer\HR
```

Users can access shared resources from multiple systems.

---

# What is a Print Server?

A Print Server manages printers in a network.

Benefits:

* Centralized Printer Management
* Easier Driver Distribution
* Reduced Administration

---

# Print Server Example

```text
Employees
      ↓
Print Server
      ↓
Network Printer
```

---

# Benefits of Print Servers

* Central Management
* Shared Printing
* Queue Management

---

# What is IIS?

IIS stands for:

```text
Internet Information Services
```

Microsoft's web server software.

Used to host:

* Websites
* Web Applications
* APIs

---

# IIS Supports

* HTTP
* HTTPS
* ASP.NET Applications

---

# Example

A company website:

```text
www.company.com
```

may be hosted on IIS.

---

# Remote Desktop Services (RDS)

Allows remote access to Windows servers and desktops.

Administrators can:

* Manage servers remotely
* Troubleshoot systems
* Access applications

---

# Remote Desktop Protocol (RDP)

Used by Remote Desktop Services.

Default Port:

```text
3389
```

Important Interview Question.

---

# Common Windows Server Roles

| Role         | Purpose                  |
| ------------ | ------------------------ |
| AD DS        | User & Domain Management |
| DNS          | Name Resolution          |
| DHCP         | IP Address Assignment    |
| File Server  | File Sharing             |
| Print Server | Printer Management       |
| IIS          | Website Hosting          |
| RDS          | Remote Access            |

---

# Quick Revision

## DHCP

Automatically assigns:

* IP Address
* Gateway
* DNS

---

## DHCP Process

DORA

* Discover
* Offer
* Request
* Acknowledge

---

## DNS

Converts names into IP addresses.

---

## File Server

Stores and shares files.

---

## Print Server

Manages network printers.

---

## IIS

Microsoft Web Server.

---

## RDP Port

3389

---

# Most Asked TCS ITIS Questions

### What is DHCP?

Protocol that automatically assigns IP addresses.

---

### What is the DHCP DORA Process?

Discover → Offer → Request → Acknowledge

---

### What is DNS?

Service that converts domain names into IP addresses.

---

### What is a File Server?

Server used for centralized file storage and sharing.

---

### What is a Print Server?

Server used to manage printers and print jobs.

---

### What does IIS stand for?

Internet Information Services.

---

### Which Windows Server role hosts websites?

IIS.

---

### What is the default port of Remote Desktop (RDP)?

3389.

---

### What is a DHCP Scope?

A range of IP addresses available for assignment.

---

### What is a DHCP Reservation?

Permanent IP assignment for a specific device using its MAC address.

# Windows Server Administration & Troubleshooting

## What is Windows Server Administration?

Windows Server Administration involves:

* Managing users
* Monitoring servers
* Troubleshooting issues
* Managing services
* Applying updates
* Maintaining security

System Administrators ensure servers remain:

* Available
* Secure
* Reliable

---

# Server Administration Tools

Common Windows administration tools:

| Tool                | Purpose                |
| ------------------- | ---------------------- |
| Server Manager      | Manage Server Roles    |
| Event Viewer        | View Logs              |
| Services            | Manage Services        |
| Task Scheduler      | Automate Tasks         |
| Device Manager      | Manage Hardware        |
| Performance Monitor | Monitor Performance    |
| Task Manager        | View Running Processes |

---

# Event Viewer

One of the most important troubleshooting tools.

Used to view:

* Errors
* Warnings
* Information Logs
* Security Events

Open:

```text
eventvwr.msc
```

---

# Why Event Viewer?

When something fails:

* Login Problems
* Service Failures
* Application Crashes

Administrators check Event Viewer first.

---

# Main Event Viewer Logs

## Application Log

Stores:

* Application Errors
* Software Events

Example:

```text
Microsoft Office Crash
```

---

## Security Log

Stores:

* Login Events
* Failed Login Attempts
* Permission Changes

Important for auditing.

---

## System Log

Stores:

* Driver Issues
* Hardware Events
* System Errors

---

# Event Types

### Information

Normal activity.

### Warning

Potential issue.

### Error

Problem occurred.

### Critical

Serious system issue.

---

# Services

Windows runs many background services.

Examples:

* DNS Service
* DHCP Service
* Print Spooler
* Windows Update

Open:

```text
services.msc
```

---

# Service States

| State   | Meaning               |
| ------- | --------------------- |
| Running | Service Active        |
| Stopped | Service Inactive      |
| Paused  | Temporarily Suspended |

---

# Common Troubleshooting Example

Problem:

Printer not working.

Check:

```text
Print Spooler Service
```

Often the service is stopped.

---

# Task Scheduler

Used to automate tasks.

Open:

```text
taskschd.msc
```

Examples:

* Automatic Backups
* Scheduled Scripts
* Disk Cleanup

---

# Benefits of Task Scheduler

* Automation
* Reduced Manual Work
* Consistent Operations

---

# Device Manager

Used to manage hardware devices.

Open:

```text
devmgmt.msc
```

---

# Device Manager Functions

* View Devices
* Update Drivers
* Disable Devices
* Troubleshoot Hardware

---

# Common Hardware Issues

### Missing Driver

Symptoms:

* Device Not Working

Solution:

Install Driver.

---

### Yellow Warning Icon

Indicates:

* Driver Problem
* Hardware Issue

---

# Task Manager

Useful for monitoring:

* CPU Usage
* Memory Usage
* Running Processes

Open:

```text
Ctrl + Shift + Esc
```

---

# Performance Monitor

Advanced monitoring tool.

Open:

```text
perfmon
```

Monitors:

* CPU
* Memory
* Disk
* Network

---

# Performance Counters

### Processor

Measures CPU utilization.

---

### Memory

Measures RAM usage.

---

### Disk

Measures storage performance.

---

### Network

Measures network traffic.

---

# High CPU Usage

Common Causes:

* Background Applications
* Malware
* Infinite Loops
* Heavy Processes

Troubleshooting:

Use:

```text
Task Manager
```

or

```text
Performance Monitor
```

---

# High Memory Usage

Symptoms:

* Slow System
* Application Crashes

Check:

```text
Task Manager
```

for memory-consuming processes.

---

# Windows Update

Keeps systems secure.

Provides:

* Security Fixes
* Bug Fixes
* Feature Updates

---

# Why Updates Matter?

Protect against:

* Vulnerabilities
* Malware
* Security Threats

---

# Backup

Backup = Copy of important data.

Purpose:

Recover from:

* Accidental Deletion
* Hardware Failure
* Malware

---

# Backup Types

## Full Backup

Copies all data.

---

## Incremental Backup

Copies only changed data since last backup.

---

## Differential Backup

Copies all changes since last full backup.

---

# Restore

Restore returns backed-up data.

Example:

```text
Backup
   ↓
Failure
   ↓
Restore
```

---

# Safe Mode

Special startup mode.

Loads:

* Essential Drivers
* Basic Services

Used for troubleshooting.

---

# Why Use Safe Mode?

Useful when:

* Driver Problems
* Malware Issues
* Startup Failures

---

# System Restart Troubleshooting

Problem:

Server restarting unexpectedly.

Check:

1. Event Viewer
2. System Logs
3. Hardware Health
4. Recent Updates

---

# User Cannot Login

Troubleshooting Steps:

1. Verify Username
2. Verify Password
3. Check Account Lockout
4. Verify Domain Connectivity
5. Check Domain Controller

---

# DNS Issue Scenario

Problem:

User can ping IP address but not website.

Example:

```text
Ping 8.8.8.8
Works

Ping google.com
Fails
```

Likely Cause:

```text
DNS Problem
```

---

# Network Connectivity Issue

Troubleshooting Order:

### Step 1

Check Cable/Wi-Fi

### Step 2

Check IP Address

```text
ipconfig
```

### Step 3

Ping Gateway

### Step 4

Ping External IP

### Step 5

Verify DNS

---

# Storage Full Scenario

Symptoms:

* Applications Fail
* Updates Fail
* System Slow

Check:

```text
Disk Usage
```

Solution:

* Delete Unnecessary Files
* Expand Storage
* Archive Old Data

---

# Common Administrative Commands

## Check IP

```cmd
ipconfig
```

---

## Test Connectivity

```cmd
ping
```

---

## DNS Lookup

```cmd
nslookup
```

---

## View Active Connections

```cmd
netstat
```

---

## Trace Route

```cmd
tracert
```

---

# Daily Tasks of a System Administrator

* Create Users
* Reset Passwords
* Manage Permissions
* Monitor Servers
* Review Logs
* Apply Updates
* Verify Backups
* Troubleshoot Issues

---

# Quick Revision

## Event Viewer

Used for log analysis.

---

## Services

Managed using:

```text
services.msc
```

---

## Task Scheduler

Automates tasks.

---

## Device Manager

Manages hardware devices.

---

## Performance Monitor

Monitors server performance.

---

## Safe Mode

Loads only essential drivers and services.

---

## Backup

Creates data copies.

---

## Restore

Recovers data from backups.

---

# Most Asked TCS ITIS Questions

### What is Event Viewer used for?

Viewing system, application, and security logs.

---

### Which tool manages Windows services?

services.msc

---

### Which service is commonly checked when printers stop working?

Print Spooler.

---

### What is Task Scheduler used for?

Automating tasks.

---

### What is Safe Mode?

A diagnostic startup mode that loads only essential drivers and services.

---

### Which tool monitors CPU and memory usage?

Performance Monitor.

---

### What command displays IP configuration?

ipconfig

---

### User can ping IP but not domain name. Likely cause?

DNS Issue.

---

### What is the purpose of backups?

To recover data after failures.

---

### What should be checked first during network troubleshooting?

Physical connectivity (cable/Wi-Fi).


