# Cloud Computing Fundamentals

## What is Cloud Computing?

Cloud Computing is the delivery of computing services over the Internet instead of using local computers or on-premise servers.

These services include:

* Servers
* Storage
* Databases
* Networking
* Software
* Analytics
* Security

Instead of buying and maintaining physical infrastructure, organizations can rent resources from cloud providers and pay only for what they use.

---

# Traditional IT vs Cloud Computing

## Traditional IT Infrastructure

In traditional environments, organizations must:

* Purchase servers
* Maintain hardware
* Configure networking
* Manage storage
* Handle backups
* Pay for power and cooling

Problems:

* High upfront cost
* Complex maintenance
* Limited scalability

---

## Cloud Computing

Resources are provided through the Internet.

Advantages:

* No hardware purchase required
* Pay-as-you-go pricing
* Easy scalability
* High availability
* Faster deployment

---

# Real-Life Example

Imagine you want to store photos.

### Traditional Method

Buy:

* Hard drive
* Storage device

Manage everything yourself.

---

### Cloud Method

Use:

* Google Drive
* OneDrive
* Dropbox

Store files online and access them anywhere.

This is a simple example of cloud computing.

---

# Why Cloud Computing?

Organizations adopt cloud because it provides:

### Cost Efficiency

No need to purchase expensive hardware.

---

### Scalability

Resources can be increased or decreased based on demand.

Example:

During a sale event, an e-commerce website can temporarily increase server capacity.

---

### Flexibility

Access services from anywhere with Internet connectivity.

---

### Reliability

Cloud providers maintain multiple data centers.

If one server fails, another can continue serving users.

---

### Disaster Recovery

Data backups and recovery are easier.

---

# Characteristics of Cloud Computing

According to NIST, cloud computing has five essential characteristics.

---

## 1. On-Demand Self-Service

Users can provision resources whenever needed.

Example:

Creating a virtual machine within minutes.

---

## 2. Broad Network Access

Services are accessible through the Internet.

Devices:

* Laptop
* Mobile
* Tablet

---

## 3. Resource Pooling

Resources are shared among multiple customers.

Example:

One data center serving thousands of organizations.

---

## 4. Rapid Elasticity

Resources can scale automatically.

Example:

Website traffic increases suddenly.

Cloud automatically adds resources.

---

## 5. Measured Service

Usage is monitored and billed accordingly.

Example:

Pay only for storage actually used.

---

# Types of Cloud Deployment Models

There are four major deployment models.

---

# 1. Public Cloud

Infrastructure is owned and managed by cloud providers.

Examples:

* AWS
* Microsoft Azure
* Google Cloud

Advantages:

* Low cost
* Easy deployment
* High scalability

Example:

A startup hosting its website on AWS.

---

# 2. Private Cloud

Infrastructure is dedicated to a single organization.

Advantages:

* Better control
* Higher security

Disadvantages:

* Expensive

Example:

A bank maintaining its own cloud environment.

---

# 3. Hybrid Cloud

Combination of:

* Public Cloud
* Private Cloud

Advantages:

* Flexibility
* Better resource utilization

Example:

Sensitive data stored privately while applications run in public cloud.

---

# 4. Community Cloud

Shared by organizations with similar requirements.

Example:

Government departments sharing infrastructure.

---

# Cloud Service Models

One of the most important interview topics.

Three major service models:

1. IaaS
2. PaaS
3. SaaS

---

# IaaS (Infrastructure as a Service)

Cloud provider offers:

* Servers
* Storage
* Networking
* Virtual Machines

Customer manages:

* Operating System
* Applications
* Data

Examples:

* Amazon EC2
* Azure Virtual Machines

---

# PaaS (Platform as a Service)

Cloud provider manages:

* Infrastructure
* Operating System
* Runtime Environment

Customer manages:

* Applications
* Data

Examples:

* Google App Engine
* Azure App Service

Used by developers to deploy applications quickly.

---

# SaaS (Software as a Service)

Cloud provider manages everything.

Users simply use the application.

Examples:

* Gmail
* Microsoft 365
* Google Workspace
* Salesforce

Advantages:

* No installation
* No maintenance

---

# Service Model Comparison

| Feature                | IaaS           | PaaS           | SaaS           |
| ---------------------- | -------------- | -------------- | -------------- |
| Infrastructure         | Cloud Provider | Cloud Provider | Cloud Provider |
| OS Management          | Customer       | Provider       | Provider       |
| Application Management | Customer       | Customer       | Provider       |
| End User Access        | No             | No             | Yes            |

---

# Virtualization

Foundation of cloud computing.

Virtualization allows multiple virtual machines to run on a single physical server.

Benefits:

* Better resource utilization
* Reduced cost
* Isolation between workloads

---

# Hypervisor

Software responsible for creating and managing virtual machines.

Examples:

* VMware ESXi
* Hyper-V
* KVM
* VirtualBox

---

# Types of Hypervisors

## Type 1 Hypervisor

Runs directly on hardware.

Examples:

* VMware ESXi
* Hyper-V

Advantages:

* Better performance
* Enterprise usage

---

## Type 2 Hypervisor

Runs on top of an operating system.

Examples:

* VirtualBox
* VMware Workstation

Advantages:

* Easy to use

Common for learning and testing.

---

# Benefits of Cloud Computing

* Cost Savings
* Scalability
* Reliability
* Flexibility
* Faster Deployment
* Global Accessibility
* Automatic Updates
* Backup & Recovery

---

# Challenges of Cloud Computing

* Internet Dependency
* Security Concerns
* Vendor Lock-In
* Compliance Requirements
* Downtime Risks

---

# Quick Revision

## Deployment Models

* Public Cloud
* Private Cloud
* Hybrid Cloud
* Community Cloud

---

## Service Models

* IaaS
* PaaS
* SaaS

---

## Virtualization

Allows multiple VMs on one physical machine.

---

## Hypervisors

### Type 1

* VMware ESXi
* Hyper-V

### Type 2

* VirtualBox
* VMware Workstation

---

# Most Asked TCS ITIS Questions

### What is Cloud Computing?

**Answer:** Delivery of computing services over the Internet.

---

### What are the three cloud service models?

**Answer:** IaaS, PaaS, SaaS

---

### Which service model provides complete software access to end users?

**Answer:** SaaS

---

### Which cloud deployment model combines public and private clouds?

**Answer:** Hybrid Cloud

---

### What is virtualization?

**Answer:** Running multiple virtual machines on a single physical server.

---

### Which hypervisor runs directly on hardware?

**Answer:** Type 1 Hypervisor

---

### Give an example of SaaS.

**Answer:** Gmail, Microsoft 365, Salesforce

---

### Give an example of IaaS.

**Answer:** Amazon EC2, Azure Virtual Machines

# AWS, Azure & Google Cloud Fundamentals

## Major Cloud Providers

The three largest cloud providers are:

### Amazon Web Services (AWS)

Launched by Amazon in 2006.

Market Leader in Cloud Computing.

Official Website:

* Amazon Web Services (AWS)

---

### Microsoft Azure

Cloud platform developed by Microsoft.

Widely used by enterprises.

Official Website:

* Microsoft Azure

---

### Google Cloud Platform (GCP)

Cloud platform developed by Google.

Popular for:

* Data Analytics
* Machine Learning
* AI Services

Official Website:

* Google Cloud Platform

---

# Why Organizations Use Cloud Providers

Cloud providers offer:

* Virtual Machines
* Storage
* Databases
* Networking
* Security
* Backup Services
* AI & Analytics

Organizations pay only for resources used.

---

# Cloud Regions

A Region is a geographical area containing cloud infrastructure.

Examples:

* Mumbai
* Singapore
* London
* Frankfurt
* Virginia

Why Regions Matter:

* Lower latency
* Regulatory compliance
* Disaster recovery

Example:

Indian users typically experience lower latency when services are hosted in the Mumbai region.

---

# Availability Zones (AZ)

Each region contains multiple Availability Zones.

Availability Zone:

* One or more data centers
* Independent power supply
* Independent networking

Example:

```text id="az1"
Mumbai Region
 ├─ AZ-1
 ├─ AZ-2
 └─ AZ-3
```

Benefits:

* High Availability
* Fault Tolerance

---

# AWS Fundamentals

AWS is the most commonly referenced cloud platform in IT infrastructure interviews.

---

# Amazon EC2

EC2 = Elastic Compute Cloud

Purpose:

Provides Virtual Machines.

Used For:

* Hosting websites
* Running applications
* Application servers

Example:

Creating a Windows or Linux server in AWS.

---

# EC2 Benefits

* Scalable
* Pay-as-you-go
* Multiple OS choices
* Easy deployment

---

# Amazon S3

S3 = Simple Storage Service

Purpose:

Object Storage Service

Used For:

* File storage
* Backups
* Media files
* Static website hosting

Examples:

* Images
* Videos
* Documents

---

# S3 Characteristics

* Highly Durable
* Highly Available
* Scalable

---

# Amazon RDS

RDS = Relational Database Service

Purpose:

Managed database service.

Supported Databases:

* MySQL
* PostgreSQL
* MariaDB
* SQL Server

Benefits:

* Automated Backups
* High Availability
* Reduced Administration

---

# Amazon VPC

VPC = Virtual Private Cloud

Purpose:

Create a private network within AWS.

Functions:

* Network Isolation
* IP Address Management
* Subnets
* Security Controls

Think of VPC as your own private data center inside AWS.

---

# AWS IAM

IAM = Identity and Access Management

Purpose:

Manage:

* Users
* Groups
* Roles
* Permissions

Benefits:

* Access Control
* Security Management

Example:

Allowing one employee access to storage but not databases.

---

# AWS Security Group

Acts as a virtual firewall.

Controls:

* Inbound Traffic
* Outbound Traffic

Example:

Allow:

```text id="aws1"
HTTP → Port 80
HTTPS → Port 443
SSH → Port 22
```

Block all other traffic.

---

# AWS CloudWatch

Purpose:

Monitoring Service

Monitors:

* CPU Usage
* Memory Metrics
* Network Traffic
* Logs

---

# Microsoft Azure Fundamentals

Azure is heavily used by enterprises and organizations already using Microsoft products.

---

# Azure Virtual Machine (VM)

Equivalent of:

```text id="azure1"
AWS EC2
```

Purpose:

Virtual Server Hosting

Supports:

* Windows
* Linux

---

# Azure Storage

Equivalent of:

```text id="azure2"
AWS S3
```

Used For:

* Files
* Backups
* Archives

---

# Azure Active Directory (Azure AD)

Identity and access management service.

Functions:

* Authentication
* Authorization
* Single Sign-On (SSO)

Example:

Microsoft 365 Login.

---

# Azure Virtual Network (VNet)

Equivalent of:

```text id="azure3"
AWS VPC
```

Provides:

* Network Isolation
* Private Networking

---

# Azure Monitor

Equivalent of:

```text id="azure4"
AWS CloudWatch
```

Purpose:

Monitoring and diagnostics.

---

# Google Cloud Platform (GCP)

Google's cloud platform.

Strong in:

* AI
* Machine Learning
* Big Data

---

# Compute Engine

Equivalent of:

```text id="gcp1"
AWS EC2
Azure VM
```

Purpose:

Virtual Machines

---

# Cloud Storage

Equivalent of:

```text id="gcp2"
AWS S3
```

Purpose:

Object Storage

---

# Cloud SQL

Equivalent of:

```text id="gcp3"
AWS RDS
```

Managed relational database service.

---

# IAM (Google Cloud)

Purpose:

User and permission management.

Similar to AWS IAM.

---

# Cloud Service Mapping

| Function            | AWS        | Azure              | GCP              |
| ------------------- | ---------- | ------------------ | ---------------- |
| Virtual Machine     | EC2        | Azure VM           | Compute Engine   |
| Storage             | S3         | Azure Storage      | Cloud Storage    |
| Database            | RDS        | Azure SQL Database | Cloud SQL        |
| Private Network     | VPC        | VNet               | VPC              |
| Identity Management | IAM        | Azure AD           | IAM              |
| Monitoring          | CloudWatch | Azure Monitor      | Cloud Monitoring |

---

# Shared Responsibility Model

Very important interview concept.

Cloud Provider Responsible For:

* Physical Security
* Hardware
* Networking Infrastructure
* Data Center Operations

Customer Responsible For:

* User Access
* Passwords
* Application Security
* Data Protection

---

# Example

If a user sets a weak password:

Responsibility:

```text id="shared1"
Customer
```

If a physical server fails:

Responsibility:

```text id="shared2"
Cloud Provider
```

---

# Benefits of Cloud Providers

* High Availability
* Scalability
* Security
* Disaster Recovery
* Global Infrastructure

---

# Quick Revision

## AWS

* EC2 → Virtual Machines
* S3 → Storage
* RDS → Database
* VPC → Networking
* IAM → Access Management
* CloudWatch → Monitoring

---

## Azure

* Azure VM
* Azure Storage
* Azure AD
* VNet
* Azure Monitor

---

## GCP

* Compute Engine
* Cloud Storage
* Cloud SQL
* IAM

---

# Most Asked TCS ITIS Questions

### What does EC2 stand for?

**Answer:** Elastic Compute Cloud

---

### Which AWS service is used for object storage?

**Answer:** Amazon S3

---

### Which AWS service is used for databases?

**Answer:** Amazon RDS

---

### What is AWS IAM used for?

**Answer:** Identity and Access Management

---

### What is a VPC?

**Answer:** Virtual Private Cloud

---

### What is the Azure equivalent of EC2?

**Answer:** Azure Virtual Machine

---

### What is the Azure equivalent of AWS VPC?

**Answer:** Azure Virtual Network (VNet)

---

### What is an Availability Zone?

**Answer:** One or more isolated data centers within a cloud region.

---

### Who is responsible for physical security in the cloud?

**Answer:** Cloud Provider

---

### Who is responsible for user passwords?

**Answer:** Customer

# Cloud Security, Virtualization, Containers & DevOps Basics

## What is Virtualization?

Virtualization is the technology that allows multiple virtual machines (VMs) to run on a single physical server.

Without virtualization:

```text
1 Server = 1 Operating System
```

With virtualization:

```text
1 Server
   ├── VM 1 (Windows)
   ├── VM 2 (Linux)
   ├── VM 3 (Ubuntu)
   └── VM 4 (CentOS)
```

Multiple operating systems can share the same hardware resources.

---

# Why Virtualization?

Benefits:

* Better hardware utilization
* Reduced cost
* Faster deployment
* Isolation between systems
* Easier backup and recovery

---

# What is a Virtual Machine (VM)?

A Virtual Machine is a software-based computer that behaves like a physical computer.

A VM has:

* CPU
* RAM
* Storage
* Operating System
* Applications

Examples:

* Windows VM
* Ubuntu VM
* Red Hat VM

---

# What is a Hypervisor?

A Hypervisor is software that creates and manages Virtual Machines.

Responsibilities:

* Create VMs
* Allocate CPU
* Allocate RAM
* Manage Storage
* Manage Networking

---

# Types of Hypervisors

## Type 1 Hypervisor (Bare Metal)

Runs directly on hardware.

```text
Hardware
   ↓
Hypervisor
   ↓
Virtual Machines
```

Examples:

* VMware ESXi
* Microsoft Hyper-V
* Xen

Advantages:

* Better performance
* Higher security
* Enterprise usage

---

## Type 2 Hypervisor

Runs on top of an operating system.

```text
Hardware
   ↓
Operating System
   ↓
Hypervisor
   ↓
Virtual Machines
```

Examples:

* VirtualBox
* VMware Workstation

Advantages:

* Easy to install
* Suitable for learning

---

# Virtualization vs Cloud Computing

| Virtualization           | Cloud Computing                 |
| ------------------------ | ------------------------------- |
| Technology               | Service Model                   |
| Creates VMs              | Delivers services over Internet |
| Runs locally or remotely | Usually Internet-based          |
| Foundation of cloud      | Uses virtualization internally  |

---

# What are Containers?

Containers package:

* Application
* Dependencies
* Libraries
* Configuration

into a single unit.

Goal:

Run applications consistently across environments.

---

# Why Containers?

Problem:

Application works on Developer Machine but fails on Production Server.

Container solves this issue by packaging everything required.

---

# Docker

Docker is the most popular container platform.

Functions:

* Build Containers
* Run Containers
* Deploy Containers

---

# Docker Components

## Docker Image

Blueprint of a container.

Contains:

* Application
* Libraries
* Dependencies

---

## Docker Container

Running instance of a Docker Image.

Think:

```text
Image = Class
Container = Object
```

---

## Docker Hub

Repository for storing Docker images.

Similar to:

```text
GitHub for Docker Images
```

---

# Virtual Machines vs Containers

| Feature        | Virtual Machine | Container |
| -------------- | --------------- | --------- |
| OS Included    | Yes             | No        |
| Size           | Large           | Small     |
| Startup Time   | Slow            | Fast      |
| Resource Usage | High            | Low       |
| Performance    | Lower           | Better    |

---

# Kubernetes

Kubernetes (K8s) is a container orchestration platform.

Purpose:

Manage large numbers of containers.

---

# Why Kubernetes?

Suppose:

```text
5 Containers
```

Easy to manage manually.

But:

```text
500 Containers
```

Requires automation.

Kubernetes provides:

* Scaling
* Load Balancing
* Self-Healing
* Deployment Management

---

# Cloud Security Fundamentals

Cloud security protects:

* Data
* Applications
* Infrastructure

from unauthorized access and cyber threats.

---

# CIA Triad

Most important security concept.

---

## Confidentiality

Ensure data is accessible only to authorized users.

Examples:

* Passwords
* Encryption
* Access Control

---

## Integrity

Ensure data remains accurate and unmodified.

Examples:

* Hashing
* Checksums

---

## Availability

Ensure systems remain accessible.

Examples:

* Backup Systems
* Redundant Servers

---

# Authentication vs Authorization

Very common interview question.

---

## Authentication

Verifies identity.

Question:

```text
Who are you?
```

Example:

* Username
* Password

---

## Authorization

Determines permissions.

Question:

```text
What can you access?
```

Example:

Admin can delete files.

Normal user cannot.

---

# Multi-Factor Authentication (MFA)

Requires multiple verification methods.

Examples:

1. Password
2. OTP
3. Fingerprint

Benefits:

* Increased Security
* Reduced Unauthorized Access

---

# Encryption

Converts readable data into unreadable form.

Purpose:

Protect sensitive information.

Example:

```text
HELLO
 ↓
Encrypted Text
```

Only authorized users can decrypt it.

---

# Data at Rest vs Data in Transit

## Data at Rest

Stored data.

Examples:

* Hard Drives
* Databases
* Cloud Storage

---

## Data in Transit

Moving data.

Examples:

* Internet Traffic
* Emails
* API Requests

---

# Backup

Backup = Copy of data.

Purpose:

Recover information after:

* Failure
* Deletion
* Attack

---

# Disaster Recovery (DR)

Plan for restoring systems after major incidents.

Examples:

* Flood
* Fire
* Data Center Failure
* Cyber Attack

---

# RPO (Recovery Point Objective)

Maximum acceptable data loss.

Example:

```text
RPO = 1 Hour
```

Maximum loss allowed:

1 hour of data.

---

# RTO (Recovery Time Objective)

Maximum acceptable downtime.

Example:

```text
RTO = 2 Hours
```

System must be restored within 2 hours.

---

# What is DevOps?

DevOps combines:

```text
Development + Operations
```

Goal:

Deliver software faster and more reliably.

---

# Traditional Approach

Developers and Operations teams worked separately.

Problems:

* Delays
* Communication issues
* Slow releases

---

# DevOps Approach

Development and Operations collaborate.

Benefits:

* Faster releases
* Better quality
* Automation
* Continuous improvement

---

# CI/CD

Frequently Asked Topic

---

## CI

Continuous Integration

Developers frequently merge code into a shared repository.

---

## CD

Continuous Delivery / Continuous Deployment

Automates software release process.

---

# Benefits of CI/CD

* Faster Delivery
* Reduced Errors
* Automated Testing
* Improved Quality

---

# Common DevOps Tools

| Tool       | Purpose                 |
| ---------- | ----------------------- |
| Git        | Version Control         |
| GitHub     | Code Repository         |
| Jenkins    | CI/CD                   |
| Docker     | Containers              |
| Kubernetes | Container Orchestration |
| Ansible    | Automation              |
| Terraform  | Infrastructure as Code  |

---

# Quick Revision

## Virtualization

* Multiple VMs on one server
* Managed by Hypervisor

---

## Containers

* Lightweight
* Fast
* Portable

---

## Docker

* Container Platform

---

## Kubernetes

* Container Management

---

## Security

CIA Triad:

* Confidentiality
* Integrity
* Availability

---

## MFA

* Password
* OTP
* Biometric

---

## DevOps

Development + Operations

---

## CI/CD

Automated software delivery pipeline

---

# Most Asked TCS ITIS Questions

### What is virtualization?

**Answer:** Running multiple virtual machines on a single physical server.

---

### What is a hypervisor?

**Answer:** Software that creates and manages virtual machines.

---

### Give an example of a Type 1 hypervisor.

**Answer:** VMware ESXi or Hyper-V.

---

### What is Docker?

**Answer:** A container platform used to build and run containers.

---

### What is Kubernetes used for?

**Answer:** Managing and orchestrating containers.

---

### What are the three pillars of the CIA Triad?

**Answer:** Confidentiality, Integrity, Availability.

---

### What is MFA?

**Answer:** Multi-Factor Authentication.

---

### What is the difference between authentication and authorization?

**Answer:** Authentication verifies identity, authorization determines permissions.

---

### What does DevOps stand for?

**Answer:** Development + Operations.

---

### What is CI/CD?

**Answer:** Continuous Integration and Continuous Delivery/Deployment.
