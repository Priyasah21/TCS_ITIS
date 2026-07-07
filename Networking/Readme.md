# Networking Fundamentals

## What is a Computer Network?

A computer network is a collection of interconnected devices that communicate and share resources with each other.

Examples of resources shared over a network:

* Files
* Printers
* Internet connection
* Applications
* Databases

---

# Why Do We Need Networking?

Networking enables:

* Communication between devices
* Resource sharing
* Centralized management
* Remote access
* Data transfer
* Internet connectivity

---

# Real-World Example

When you open a website:

1. Your device sends a request.
2. The request travels through the network.
3. The web server receives the request.
4. The server sends the webpage back.

This entire process happens within milliseconds.

---

# Types of Networks

## PAN (Personal Area Network)

A network covering a very small area around an individual.

Examples:

* Bluetooth headset
* Smartwatch connection
* Wireless keyboard

Range: Few meters

---

## LAN (Local Area Network)

Connects devices within a small geographical area.

Examples:

* Home Wi-Fi
* School computer lab
* Office network

Characteristics:

* High speed
* Low latency
* Privately managed

---

## MAN (Metropolitan Area Network)

Connects multiple LANs within a city.

Examples:

* City-wide cable networks
* Municipal networks

Range: Several kilometers

---

## WAN (Wide Area Network)

Connects networks across large geographical distances.

Examples:

* Internet
* Corporate branch networks

Characteristics:

* Large coverage
* Higher latency than LAN

---

# Network Devices

## Hub

A basic networking device.

Characteristics:

* Broadcasts data to all devices
* No intelligence
* Operates at Physical Layer

Disadvantages:

* High collisions
* Poor security

---

## Switch

Most common LAN device.

Characteristics:

* Sends data only to the intended device
* Uses MAC addresses
* Faster than a hub

Advantages:

* Reduced collisions
* Better performance

---

## Router

Connects different networks together.

Example:

* Home router connecting your LAN to the Internet

Functions:

* Routing
* Packet forwarding
* Network segmentation

---

## Modem

Modulator-Demodulator

Purpose:

* Connects your network to your Internet Service Provider (ISP)

---

## Access Point (AP)

Provides wireless connectivity.

Example:

* Office Wi-Fi Access Point

---

## Firewall

Protects networks from unauthorized access.

Functions:

* Filters traffic
* Blocks malicious requests
* Enforces security policies

---

# Data Communication Components

For communication to occur, the following are required:

## Sender

Device sending data.

Example:

Laptop

---

## Receiver

Device receiving data.

Example:

Server

---

## Message

The information being transmitted.

Examples:

* Email
* File
* Webpage request

---

## Medium

Path used to transfer data.

Examples:

* Fiber optic cable
* Ethernet cable
* Wireless signals

---

## Protocol

Rules governing communication.

Examples:

* TCP
* IP
* HTTP
* FTP

---

# Network Topologies

Topology refers to the physical or logical arrangement of devices in a network.

---

## Bus Topology

All devices share a common cable.

Advantages:

* Simple
* Low cost

Disadvantages:

* Single cable failure affects the network

---

## Star Topology

All devices connect to a central switch or hub.

Advantages:

* Easy troubleshooting
* Widely used

Disadvantages:

* Central device failure affects communication

---

## Ring Topology

Devices form a circular connection.

Data travels around the ring.

---

## Mesh Topology

Every device connects to multiple devices.

Advantages:

* High reliability

Disadvantages:

* Expensive

---

# Network Models

Networking follows standard models to ensure interoperability.

Two major models:

1. OSI Model
2. TCP/IP Model

These models are among the most frequently asked topics in ITIS assessments and interviews.

We will cover them in detail in the next section.

---

# Key Networking Terms

## Bandwidth

Maximum amount of data that can be transmitted per second.

Measured in:

* Mbps
* Gbps

Example:

100 Mbps Internet connection

---

## Latency

Time taken for data to travel from source to destination.

Lower latency is better.

Measured in milliseconds (ms).

---

## Throughput

Actual amount of data successfully transmitted.

---

## Packet

A small unit of data transmitted across a network.

Large files are broken into packets before transmission.

---

## Node

Any device connected to a network.

Examples:

* Computer
* Printer
* Router
* Mobile phone

---

# Quick Revision

## Types of Networks

* PAN
* LAN
* MAN
* WAN

---

## Network Devices

* Hub
* Switch
* Router
* Modem
* Access Point
* Firewall

---

## Topologies

* Bus
* Star
* Ring
* Mesh

---

## Important Terms

* Bandwidth
* Latency
* Throughput
* Packet
* Node

---

# Most Asked TCS ITIS Questions

### Which device connects different networks?

**Answer:** Router

---

### Which device operates using MAC addresses?

**Answer:** Switch

---

### Which topology is most commonly used in modern LANs?

**Answer:** Star Topology

---

### What does WAN stand for?

**Answer:** Wide Area Network

---

### What is latency?

**Answer:** Time taken for data to travel from source to destination.

---

### Which device provides wireless connectivity?

**Answer:** Access Point (AP)

---

### Which device protects a network from unauthorized access?

**Answer:** Firewall

# OSI Model & TCP/IP Model

## Why Do We Need Network Models?

When data travels from one device to another, many operations happen:

* Data formatting
* Encryption
* Addressing
* Routing
* Error checking
* Physical transmission

To standardize communication, networking uses layered models.

The two most important models are:

1. OSI Model (7 Layers)
2. TCP/IP Model (4 Layers)

---

# OSI Model (Open Systems Interconnection)

Developed by ISO (International Organization for Standardization).

The OSI model contains 7 layers.

```text id="osi1"
7. Application
6. Presentation
5. Session
4. Transport
3. Network
2. Data Link
1. Physical
```

---

# Memory Trick

### Top to Bottom

```text id="osi2"
All
People
Seem
To
Need
Data
Processing
```

Application → Presentation → Session → Transport → Network → Data Link → Physical

---

### Bottom to Top

```text id="osi3"
Please
Do
Not
Throw
Sausage
Pizza
Away
```

Physical → Data Link → Network → Transport → Session → Presentation → Application

---

# Layer 7 – Application Layer

Closest layer to the user.

Provides network services directly to applications.

Examples:

* Web Browsers
* Email Clients
* FTP Clients

Protocols:

* HTTP
* HTTPS
* FTP
* SMTP
* POP3
* IMAP
* DNS

Examples:

* Opening Google
* Sending Email
* Downloading Files

---

# Layer 6 – Presentation Layer

Responsible for:

* Data translation
* Encryption
* Compression

Functions:

* Converts data formats
* Encrypts sensitive information
* Compresses data before transmission

Examples:

* SSL/TLS encryption
* JPEG
* PNG
* MP3

---

# Layer 5 – Session Layer

Responsible for establishing and managing communication sessions.

Functions:

* Session establishment
* Session maintenance
* Session termination

Examples:

* Video conferencing
* Database sessions

---

# Layer 4 – Transport Layer

Responsible for end-to-end communication.

Functions:

* Segmentation
* Error recovery
* Flow control
* Reliability

Protocols:

### TCP

Transmission Control Protocol

Characteristics:

* Reliable
* Connection-oriented
* Error checking
* Ordered delivery

Examples:

* HTTPS
* Banking transactions
* Email

---

### UDP

User Datagram Protocol

Characteristics:

* Faster
* Connectionless
* No guarantee of delivery

Examples:

* Video streaming
* Online gaming
* Voice calls

---

# Layer 3 – Network Layer

Responsible for logical addressing and routing.

Functions:

* IP addressing
* Routing packets
* Path determination

Protocols:

* IPv4
* IPv6
* ICMP

Device:

* Router

Address Used:

* IP Address

Example:

```text id="osi4"
192.168.1.10
```

---

# Layer 2 – Data Link Layer

Responsible for node-to-node delivery.

Functions:

* MAC addressing
* Frame creation
* Error detection

Device:

* Switch

Address Used:

* MAC Address

Example:

```text id="osi5"
00:1A:2B:3C:4D:5E
```

---

# Layer 1 – Physical Layer

Lowest OSI layer.

Responsible for actual transmission of bits.

Functions:

* Electrical signals
* Cables
* Connectors
* Wireless signals

Devices:

* Hub
* Repeater
* Cables

Data Unit:

Bits

---

# OSI Data Units

| Layer        | Data Unit |
| ------------ | --------- |
| Application  | Data      |
| Presentation | Data      |
| Session      | Data      |
| Transport    | Segment   |
| Network      | Packet    |
| Data Link    | Frame     |
| Physical     | Bits      |

---

# Encapsulation

As data moves down the OSI layers:

```text id="osi6"
Data
 ↓
Segment
 ↓
Packet
 ↓
Frame
 ↓
Bits
```

Each layer adds its own header information.

This process is called Encapsulation.

---

# Decapsulation

At the receiving end:

```text id="osi7"
Bits
 ↓
Frame
 ↓
Packet
 ↓
Segment
 ↓
Data
```

Headers are removed layer by layer.

This process is called Decapsulation.

---

# TCP/IP Model

The Internet primarily uses the TCP/IP model.

It contains 4 layers.

```text id="tcp1"
Application
Transport
Internet
Network Access
```

---

# TCP/IP vs OSI Mapping

| TCP/IP Layer   | OSI Layer                            |
| -------------- | ------------------------------------ |
| Application    | Application + Presentation + Session |
| Transport      | Transport                            |
| Internet       | Network                              |
| Network Access | Data Link + Physical                 |

---

# Protocols in TCP/IP Model

## Application Layer

Protocols:

* HTTP
* HTTPS
* FTP
* SMTP
* DNS

---

## Transport Layer

Protocols:

* TCP
* UDP

---

## Internet Layer

Protocols:

* IPv4
* IPv6
* ICMP

---

## Network Access Layer

Technologies:

* Ethernet
* Wi-Fi

---

# OSI Devices by Layer

| Layer        | Device        |
| ------------ | ------------- |
| Application  | Gateway       |
| Presentation | Gateway       |
| Session      | Gateway       |
| Transport    | Gateway       |
| Network      | Router        |
| Data Link    | Switch        |
| Physical     | Hub, Repeater |

---

# TCP vs UDP

| Feature            | TCP                 | UDP            |
| ------------------ | ------------------- | -------------- |
| Connection         | Connection-Oriented | Connectionless |
| Reliability        | Reliable            | Unreliable     |
| Speed              | Slower              | Faster         |
| Error Checking     | Yes                 | Minimal        |
| Delivery Guarantee | Yes                 | No             |

---

# Real-Life Example

When opening a website:

1. Browser creates HTTP request (Application Layer)
2. TCP establishes connection (Transport Layer)
3. IP adds source and destination addresses (Network Layer)
4. Frame is created (Data Link Layer)
5. Bits travel through cable/Wi-Fi (Physical Layer)

---

# Quick Revision

## OSI Layers

1. Application
2. Presentation
3. Session
4. Transport
5. Network
6. Data Link
7. Physical

---

## Layer Devices

* Router → Layer 3
* Switch → Layer 2
* Hub → Layer 1

---

## Addresses

* IP Address → Layer 3
* MAC Address → Layer 2

---

## Transport Protocols

* TCP
* UDP

---

## Important Protocols

* HTTP
* HTTPS
* FTP
* SMTP
* DNS

---

# Most Asked TCS ITIS Questions

### Which OSI layer is responsible for routing?

**Answer:** Network Layer (Layer 3)

---

### Which device works at Layer 2?

**Answer:** Switch

---

### Which device works at Layer 3?

**Answer:** Router

---

### Which address is used at Layer 2?

**Answer:** MAC Address

---

### Which address is used at Layer 3?

**Answer:** IP Address

---

### Which protocol is reliable: TCP or UDP?

**Answer:** TCP

---

### Which protocol is faster: TCP or UDP?

**Answer:** UDP

---

### What is the data unit at the Network Layer?

**Answer:** Packet

---

### What is encapsulation?

**Answer:** The process of adding headers as data moves down the network layers.

---

### How many layers are there in the OSI Model?

**Answer:** 7

---

### How many layers are there in the TCP/IP Model?

**Answer:** 4

# IP Addressing & Subnetting Basics

## What is an IP Address?

IP (Internet Protocol) Address is a unique logical address assigned to a device on a network.

Just like every house has a postal address, every device on a network needs an IP address for communication.

Examples:

```text id="ip1"
192.168.1.10
10.0.0.5
172.16.20.1
```

Without an IP address, devices cannot communicate over a network.

---

# Why Do We Need IP Addresses?

IP addresses help:

* Identify devices
* Locate devices on networks
* Route data correctly
* Enable internet communication

---

# Types of IP Addresses

There are two major versions:

1. IPv4
2. IPv6

---

# IPv4 Address

IPv4 = Internet Protocol Version 4

Format:

```text id="ip2"
192.168.1.10
```

Characteristics:

* 32-bit address
* Divided into 4 octets
* Each octet ranges from 0 to 255

Example:

```text id="ip3"
192 . 168 . 1 . 10
```

Each section is called an octet.

---

# IPv4 Address Range

Minimum:

```text id="ip4"
0.0.0.0
```

Maximum:

```text id="ip5"
255.255.255.255
```

Total IPv4 Addresses:

```text id="ip6"
2^32
=
4,294,967,296
```

Approximately 4.3 billion addresses.

---

# IPv6 Address

IPv6 was introduced because IPv4 addresses were running out.

Example:

```text id="ip7"
2001:0db8:85a3:0000:0000:8a2e:0370:7334
```

Characteristics:

* 128-bit address
* Uses hexadecimal values
* Much larger address space

---

# IPv4 vs IPv6

| Feature       | IPv4         | IPv6            |
| ------------- | ------------ | --------------- |
| Size          | 32-bit       | 128-bit         |
| Format        | Decimal      | Hexadecimal     |
| Example       | 192.168.1.1  | 2001:db8::1     |
| Address Space | ~4.3 Billion | Extremely Large |

---

# Public IP Address

Public IPs are accessible over the internet.

Assigned by:

* Internet Service Providers (ISPs)

Example:

```text id="ip8"
49.205.10.25
```

Public IPs must be globally unique.

---

# Private IP Address

Used inside local networks.

Cannot be directly accessed from the internet.

---

## Private IP Ranges

### Class A

```text id="ip9"
10.0.0.0
to
10.255.255.255
```

---

### Class B

```text id="ip10"
172.16.0.0
to
172.31.255.255
```

---

### Class C

```text id="ip11"
192.168.0.0
to
192.168.255.255
```

These ranges are heavily used in homes and offices.

---

# Static IP Address

Manually configured.

Characteristics:

* Fixed
* Does not change automatically

Used for:

* Servers
* Printers
* Network devices

---

# Dynamic IP Address

Assigned automatically.

Characteristics:

* Can change
* Managed by DHCP

Used for:

* Home devices
* Employee laptops
* Mobile devices

---

# DHCP (Dynamic Host Configuration Protocol)

DHCP automatically assigns:

* IP Address
* Subnet Mask
* Default Gateway
* DNS Server

Without DHCP, every device would need manual configuration.

---

# DHCP Process

Memory Trick:

```text id="ip12"
DORA
```

---

### D – Discover

Client searches for DHCP server.

---

### O – Offer

DHCP server offers an IP address.

---

### R – Request

Client requests the offered address.

---

### A – Acknowledge

Server confirms assignment.

---

# Subnet Mask

Used to identify:

* Network Portion
* Host Portion

Example:

```text id="ip13"
255.255.255.0
```

Commonly written as:

```text id="ip14"
/24
```

---

# Why Subnet Masks Are Needed

Suppose:

```text id="ip15"
IP Address = 192.168.1.100
Subnet Mask = 255.255.255.0
```

Network:

```text id="ip16"
192.168.1.0
```

Host:

```text id="ip17"
100
```

The subnet mask tells us which part represents the network and which part represents the host.

---

# CIDR Notation

CIDR = Classless Inter-Domain Routing

Examples:

```text id="ip18"
192.168.1.0/24
10.0.0.0/8
172.16.0.0/16
```

---

## Common CIDR Values

| CIDR | Subnet Mask     |
| ---- | --------------- |
| /8   | 255.0.0.0       |
| /16  | 255.255.0.0     |
| /24  | 255.255.255.0   |
| /32  | 255.255.255.255 |

---

# Default Gateway

The gateway is the device that connects your local network to other networks.

Usually:

```text id="ip19"
192.168.1.1
```

Most home routers act as the default gateway.

---

# Network ID

Identifies the network.

Example:

```text id="ip20"
IP Address: 192.168.1.50
Subnet Mask: 255.255.255.0
```

Network ID:

```text id="ip21"
192.168.1.0
```

---

# Broadcast Address

Used to communicate with all devices on a network.

Example:

```text id="ip22"
192.168.1.255
```

All hosts on the subnet receive the message.

---

# Loopback Address

Used for testing the local machine.

IPv4:

```text id="ip23"
127.0.0.1
```

Meaning:

"This computer."

---

# APIPA Address

Assigned automatically when DHCP fails.

Range:

```text id="ip24"
169.254.0.0
to
169.254.255.255
```

If you see a 169.254.x.x address, DHCP is usually not working.

---

# DNS (Domain Name System)

Converts names into IP addresses.

Example:

```text id="ip25"
google.com
↓
142.x.x.x
```

Without DNS, users would need to remember IP addresses.

---

# Quick Revision

### Private IP Ranges

* 10.0.0.0/8
* 172.16.0.0/12
* 192.168.0.0/16

---

### DHCP Process

DORA

* Discover
* Offer
* Request
* Acknowledge

---

### Special Addresses

| Address       | Purpose   |
| ------------- | --------- |
| 127.0.0.1     | Loopback  |
| 169.254.x.x   | APIPA     |
| 192.168.1.255 | Broadcast |

---

### Important Terms

* IP Address
* Subnet Mask
* Gateway
* DNS
* DHCP
* CIDR

---

# Most Asked TCS ITIS Questions

### What does DHCP stand for?

**Answer:** Dynamic Host Configuration Protocol

---

### What is the loopback address?

**Answer:** 127.0.0.1

---

### What is the purpose of DNS?

**Answer:** Converts domain names into IP addresses.

---

### Which IP range belongs to Class C private addresses?

**Answer:** 192.168.0.0 – 192.168.255.255

---

### What does APIPA indicate?

**Answer:** DHCP assignment failure.

---

### What is the purpose of a subnet mask?

**Answer:** To identify the network and host portions of an IP address.

---

### What is the commonly used subnet mask for a /24 network?

**Answer:** 255.255.255.0

---

### What is the default gateway?

**Answer:** The device that forwards traffic from the local network to other networks.

---

### Which protocol automatically assigns IP addresses?

**Answer:** DHCP

# DNS, DHCP, Ports & Protocols

## What is DNS?

DNS stands for **Domain Name System**.

DNS translates human-readable domain names into IP addresses.

Example:

```text id="dns1"
www.google.com
        ↓
142.250.x.x
```

Humans remember names easily, but computers communicate using IP addresses.

DNS acts like the Internet's phonebook.

---

# Why Do We Need DNS?

Without DNS:

```text id="dns2"
https://142.250.182.14
```

Instead of:

```text id="dns3"
https://www.google.com
```

DNS makes internet usage easier.

---

# DNS Resolution Process

Suppose a user enters:

```text id="dns4"
www.google.com
```

Step 1:

Browser checks local cache.

↓

Step 2:

Operating system checks DNS cache.

↓

Step 3:

Query sent to DNS server.

↓

Step 4:

DNS server returns IP address.

↓

Step 5:

Browser connects to destination server.

---

# Types of DNS Records

## A Record

Maps:

```text id="dns5"
Domain Name → IPv4 Address
```

Example:

```text id="dns6"
google.com → 142.250.x.x
```

---

## AAAA Record

Maps:

```text id="dns7"
Domain Name → IPv6 Address
```

---

## CNAME Record

Alias for another domain.

Example:

```text id="dns8"
mail.company.com
        ↓
server.company.com
```

---

## MX Record

Mail Exchange Record.

Used for email routing.

Example:

```text id="dns9"
gmail.com mail servers
```

---

## NS Record

Name Server Record.

Identifies authoritative DNS servers.

---

# What is DHCP?

DHCP stands for:

```text id="dns10"
Dynamic Host Configuration Protocol
```

Automatically assigns:

* IP Address
* Subnet Mask
* Gateway
* DNS Server

---

# Why DHCP?

Without DHCP:

Every computer would require manual network configuration.

DHCP automates the entire process.

---

# DHCP Process

Memory Trick:

```text id="dns11"
DORA
```

---

## Discover

Client searches for DHCP server.

---

## Offer

Server offers an IP address.

---

## Request

Client requests the offered address.

---

## Acknowledge

Server confirms assignment.

---

# Lease Time

DHCP provides an IP address for a limited duration.

Example:

```text id="dns12"
24 Hours
```

After lease expiration:

* Renew IP
* Request new IP

---

# What is a Port?

A port is a logical communication endpoint.

Think of:

```text id="dns13"
IP Address = Building
Port = Room Number
```

Example:

```text id="dns14"
192.168.1.10:80
```

IP identifies the device.

Port identifies the service.

---

# Port Number Ranges

| Range       | Category         |
| ----------- | ---------------- |
| 0–1023      | Well-Known Ports |
| 1024–49151  | Registered Ports |
| 49152–65535 | Dynamic Ports    |

---

# Common Networking Protocols

Protocols define communication rules.

---

# HTTP

HyperText Transfer Protocol

Purpose:

* Website communication

Default Port:

```text id="dns15"
80
```

Characteristics:

* Unencrypted
* Less secure

Example:

```text id="dns16"
http://example.com
```

---

# HTTPS

HyperText Transfer Protocol Secure

Default Port:

```text id="dns17"
443
```

Characteristics:

* Encrypted
* Secure communication

Example:

```text id="dns18"
https://example.com
```

Most modern websites use HTTPS.

---

# FTP

File Transfer Protocol

Purpose:

* File transfer

Port:

```text id="dns19"
21
```

Characteristics:

* Not encrypted

---

# SFTP

Secure File Transfer Protocol

Uses:

```text id="dns20"
SSH
```

Port:

```text id="dns21"
22
```

More secure than FTP.

---

# SSH

Secure Shell

Purpose:

* Remote login
* Server administration

Port:

```text id="dns22"
22
```

Example:

```text id="dns23"
ssh user@server
```

---

# Telnet

Remote access protocol.

Port:

```text id="dns24"
23
```

Characteristics:

* Not encrypted
* Mostly replaced by SSH

---

# SMTP

Simple Mail Transfer Protocol

Purpose:

* Sending emails

Port:

```text id="dns25"
25
```

---

# POP3

Post Office Protocol Version 3

Purpose:

* Download emails

Port:

```text id="dns26"
110
```

---

# IMAP

Internet Message Access Protocol

Purpose:

* Access emails on server

Port:

```text id="dns27"
143
```

Advantage:

* Emails remain on server

---

# DNS Protocol

Purpose:

Domain Name Resolution

Port:

```text id="dns28"
53
```

Protocol:

* UDP (usually)
* TCP (sometimes)

---

# DHCP Protocol

Ports:

```text id="dns29"
67
68
```

Server:

```text id="dns30"
67
```

Client:

```text id="dns31"
68
```

---

# SNMP

Simple Network Management Protocol

Purpose:

* Network monitoring
* Device management

Port:

```text id="dns32"
161
```

Used by:

* Routers
* Switches
* Servers

---

# ICMP

Internet Control Message Protocol

Used for:

* Diagnostics
* Error reporting

Example:

```text id="dns33"
ping
```

Uses ICMP.

---

# ARP

Address Resolution Protocol

Purpose:

Convert:

```text id="dns34"
IP Address
     ↓
MAC Address
```

Example:

```text id="dns35"
192.168.1.10
     ↓
00:1A:2B:3C:4D:5E
```

---

# Common Port Numbers

| Protocol | Port  |
| -------- | ----- |
| HTTP     | 80    |
| HTTPS    | 443   |
| FTP      | 21    |
| SSH      | 22    |
| Telnet   | 23    |
| SMTP     | 25    |
| DNS      | 53    |
| DHCP     | 67,68 |
| POP3     | 110   |
| IMAP     | 143   |
| SNMP     | 161   |

---

# Important Protocol Comparison

## HTTP vs HTTPS

| Feature    | HTTP | HTTPS |
| ---------- | ---- | ----- |
| Security   | No   | Yes   |
| Encryption | No   | Yes   |
| Port       | 80   | 443   |

---

## FTP vs SFTP

| Feature    | FTP | SFTP |
| ---------- | --- | ---- |
| Port       | 21  | 22   |
| Security   | Low | High |
| Encryption | No  | Yes  |

---

## Telnet vs SSH

| Feature    | Telnet | SSH  |
| ---------- | ------ | ---- |
| Port       | 23     | 22   |
| Encryption | No     | Yes  |
| Security   | Low    | High |

---

# Quick Revision

### DNS

Converts:

```text id="dns36"
Domain Name
     ↓
IP Address
```

---

### DHCP

Automatically assigns:

* IP Address
* Gateway
* DNS
* Subnet Mask

---

### ARP

Converts:

```text id="dns37"
IP → MAC
```

---

### ICMP

Used by:

```text id="dns38"
ping
```

---

# Most Asked TCS ITIS Questions

### Which protocol converts domain names to IP addresses?

**Answer:** DNS

---

### Which protocol automatically assigns IP addresses?

**Answer:** DHCP

---

### Which protocol is used by ping?

**Answer:** ICMP

---

### Which protocol converts IP addresses into MAC addresses?

**Answer:** ARP

---

### What is the default port of HTTPS?

**Answer:** 443

---

### What is the default port of HTTP?

**Answer:** 80

---

### Which protocol is a secure replacement for Telnet?

**Answer:** SSH

---

### Which protocol is used to send emails?

**Answer:** SMTP

---

### Which protocol is used to access emails while keeping them on the server?

**Answer:** IMAP

---

### What does SNMP stand for?

**Answer:** Simple Network Management Protocol

# Network Troubleshooting & Networking Commands

## Why Network Troubleshooting Matters

In IT Infrastructure roles, users often report issues such as:

* Internet not working
* Website not opening
* Unable to access server
* Email issues
* Slow network performance
* DNS failures

Network troubleshooting helps identify and resolve these problems systematically.

---

# Basic Troubleshooting Approach

When a network issue occurs:

### Step 1

Check physical connectivity.

Questions:

* Is the cable connected?
* Is Wi-Fi enabled?
* Is the router powered on?

---

### Step 2

Verify IP configuration.

---

### Step 3

Check connectivity.

---

### Step 4

Verify DNS resolution.

---

### Step 5

Trace the route.

---

### Step 6

Check ports and services.

---

# ping Command

The most commonly used troubleshooting command.

Purpose:

* Verify connectivity
* Measure response time
* Detect packet loss

---

## Syntax

```bash
ping hostname
```

Example:

```bash
ping google.com
```

---

## Sample Output

```text
Reply from 142.x.x.x
time=20ms
```

---

## What ping Uses

Protocol:

```text
ICMP
```

---

## Send Limited Packets

Linux:

```bash
ping -c 4 google.com
```

Windows:

```cmd
ping -n 4 google.com
```

---

# Understanding Ping Results

## Successful Ping

```text
Packets Sent = 4
Packets Received = 4
```

Connectivity exists.

---

## Request Timed Out

```text
Request Timed Out
```

Possible causes:

* Device offline
* Firewall blocking ICMP
* Network failure

---

# traceroute / tracert

Shows the path packets take to reach a destination.

---

## Linux

```bash
traceroute google.com
```

---

## Windows

```cmd
tracert google.com
```

---

## Why Use It?

Helps identify where a connection is failing.

Example:

```text
PC
 ↓
Router
 ↓
ISP
 ↓
Destination
```

---

# ipconfig (Windows)

Displays network configuration.

---

## Show IP Information

```cmd
ipconfig
```

Displays:

* IP Address
* Subnet Mask
* Default Gateway

---

## Detailed Information

```cmd
ipconfig /all
```

Displays:

* DNS Server
* MAC Address
* DHCP Information

---

## Renew DHCP Address

```cmd
ipconfig /renew
```

---

## Release Current IP

```cmd
ipconfig /release
```

---

# ifconfig (Linux - Legacy)

Displays network interface information.

```bash
ifconfig
```

Still seen in older Linux systems.

---

# ip addr (Linux)

Modern replacement for ifconfig.

```bash
ip addr
```

or

```bash
ip a
```

Displays:

* IP Address
* Network Interfaces
* Interface Status

---

# hostname Command

Displays system hostname.

```bash
hostname
```

Example:

```text
SERVER01
```

---

# nslookup Command

Used for DNS troubleshooting.

Purpose:

```text
Domain Name
        ↓
IP Address
```

---

## Example

```bash
nslookup google.com
```

Output:

```text
IP Address returned
```

---

## When to Use

If:

* Website not opening
* DNS suspected

---

# netstat Command

Displays:

* Active connections
* Listening ports
* Routing information

---

## Example

```bash
netstat -an
```

---

## Common Uses

Check:

* Open ports
* Established connections
* Services listening

---

# ss Command

Modern Linux replacement for netstat.

---

## Example

```bash
ss -tuln
```

Displays:

* TCP ports
* UDP ports
* Listening services

---

# arp Command

Displays ARP table.

Purpose:

```text
IP Address
     ↓
MAC Address
```

---

## Example

Windows:

```cmd
arp -a
```

Linux:

```bash
arp -a
```

---

# route Command

Displays routing table.

---

## Linux

```bash
route -n
```

or

```bash
ip route
```

---

## Purpose

Shows:

* Default Gateway
* Routing paths

---

# curl Command

Transfers data from servers.

Commonly used for:

* APIs
* Website testing

---

## Example

```bash
curl https://example.com
```

---

## Check Headers Only

```bash
curl -I https://example.com
```

Useful for verifying website availability.

---

# wget Command

Downloads files from the internet.

---

## Example

```bash
wget https://example.com/file.zip
```

---

# Real-World Troubleshooting Scenarios

## Scenario 1

### Problem

User cannot access the internet.

### Steps

1. Check cable/Wi-Fi
2. Run:

```bash
ipconfig
```

or

```bash
ip addr
```

3. Verify IP address
4. Ping gateway
5. Ping Google

---

## Scenario 2

### Problem

Website not opening.

### Steps

1. Ping website

```bash
ping google.com
```

2. Check DNS

```bash
nslookup google.com
```

3. Trace route

```bash
traceroute google.com
```

---

## Scenario 3

### Problem

Server not reachable.

### Steps

1. Ping server IP
2. Verify routing table
3. Check firewall
4. Verify service ports

```bash
netstat -an
```

---

## Scenario 4

### Problem

User receives APIPA address.

Example:

```text
169.254.x.x
```

Cause:

DHCP server unavailable.

Solution:

* Verify DHCP service
* Renew IP address

```cmd
ipconfig /renew
```

---

# Common Networking Commands Summary

| Command            | Purpose                       |
| ------------------ | ----------------------------- |
| ping               | Connectivity Test             |
| tracert/traceroute | Path Analysis                 |
| ipconfig           | Windows Network Configuration |
| ifconfig           | Linux Interface Info          |
| ip addr            | Modern Linux Interface Info   |
| nslookup           | DNS Lookup                    |
| netstat            | Network Statistics            |
| ss                 | Linux Socket Information      |
| arp                | ARP Table                     |
| route              | Routing Table                 |
| curl               | Website/API Testing           |
| wget               | File Download                 |
| hostname           | Display Hostname              |

---

# Quick Revision

### DNS Issue?

Use:

```bash
nslookup
```

---

### Connectivity Issue?

Use:

```bash
ping
```

---

### Route Problem?

Use:

```bash
traceroute
```

---

### Check Open Ports?

Use:

```bash
netstat
```

or

```bash
ss
```

---

### APIPA Address?

```text
169.254.x.x
```

Usually indicates DHCP failure.

---

# Most Asked TCS ITIS Questions

### Which command is used to test connectivity?

**Answer:** ping

---

### Which protocol does ping use?

**Answer:** ICMP

---

### Which command checks DNS resolution?

**Answer:** nslookup

---

### Which command shows the route packets take?

**Answer:** traceroute / tracert

---

### Which command displays active network connections?

**Answer:** netstat

---

### Which Linux command is the modern replacement for ifconfig?

**Answer:** ip addr

---

### Which command displays the ARP table?

**Answer:** arp -a

---

### A user receives 169.254.x.x IP. What is the likely issue?

**Answer:** DHCP failure

---

### Which command displays the routing table?

**Answer:** route or ip route

---

### Which command is commonly used for API testing?

**Answer:** curl



