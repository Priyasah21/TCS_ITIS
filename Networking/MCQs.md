# Networking MCQs

## Section 1: Networking Fundamentals & OSI Model (Q1–Q25)

### Q1. What is a computer network?

A. A database system

B. A collection of interconnected devices

C. A programming language

D. An operating system

**Answer:** B

---

### Q2. Which type of network covers a small geographical area such as an office or home?

A. WAN

B. MAN

C. LAN

D. PAN

**Answer:** C

---

### Q3. Which type of network covers the largest geographical area?

A. LAN

B. PAN

C. MAN

D. WAN

**Answer:** D

---

### Q4. Which device connects different networks together?

A. Hub

B. Switch

C. Router

D. Repeater

**Answer:** C

---

### Q5. Which networking device uses MAC addresses to forward frames?

A. Router

B. Switch

C. Modem

D. Gateway

**Answer:** B

---

### Q6. Which device operates at the Physical Layer of the OSI model?

A. Router

B. Switch

C. Hub

D. Firewall

**Answer:** C

---

### Q7. Which topology is most commonly used in modern LANs?

A. Bus

B. Ring

C. Star

D. Mesh

**Answer:** C

---

### Q8. What is bandwidth?

A. Delay in communication

B. Maximum data transfer capacity

C. Packet loss

D. IP address range

**Answer:** B

---

### Q9. What is latency?

A. Network speed

B. Data storage capacity

C. Time taken for data to travel

D. Number of packets

**Answer:** C

---

### Q10. What is a packet?

A. Physical cable

B. Router

C. Small unit of transmitted data

D. MAC address

**Answer:** C

---

### Q11. How many layers are there in the OSI model?

A. 4

B. 5

C. 6

D. 7

**Answer:** D

---

### Q12. Which OSI layer is closest to the end user?

A. Physical

B. Network

C. Application

D. Session

**Answer:** C

---

### Q13. Which OSI layer is responsible for routing?

A. Transport

B. Data Link

C. Network

D. Session

**Answer:** C

---

### Q14. Which device primarily operates at the Network Layer?

A. Switch

B. Router

C. Hub

D. Repeater

**Answer:** B

---

### Q15. Which OSI layer uses MAC addresses?

A. Physical

B. Network

C. Data Link

D. Session

**Answer:** C

---

### Q16. Which address is associated with the Network Layer?

A. MAC Address

B. IP Address

C. Port Number

D. URL

**Answer:** B

---

### Q17. Which OSI layer is responsible for end-to-end communication?

A. Session

B. Transport

C. Network

D. Physical

**Answer:** B

---

### Q18. TCP and UDP belong to which layer?

A. Application

B. Transport

C. Network

D. Data Link

**Answer:** B

---

### Q19. Which protocol is connection-oriented?

A. UDP

B. IP

C. TCP

D. ICMP

**Answer:** C

---

### Q20. Which protocol is faster because it does not establish a connection?

A. TCP

B. HTTP

C. UDP

D. FTP

**Answer:** C

---

### Q21. What is the data unit at the Transport Layer?

A. Frame

B. Packet

C. Segment

D. Bit

**Answer:** C

---

### Q22. What is the data unit at the Network Layer?

A. Packet

B. Frame

C. Segment

D. Bit

**Answer:** A

---

### Q23. What is the data unit at the Data Link Layer?

A. Segment

B. Packet

C. Frame

D. Bit

**Answer:** C

---

### Q24. What is the process of adding headers as data moves down the OSI layers called?

A. Routing

B. Encapsulation

C. Fragmentation

D. Encryption

**Answer:** B

---

### Q25. Which model is primarily used on the Internet?

A. OSI Model

B. TCP/IP Model

C. Star Model

D. Hybrid Model

**Answer:** B

---

# Quick Revision

### Devices & Layers

| Device | Layer     |
| ------ | --------- |
| Hub    | Physical  |
| Switch | Data Link |
| Router | Network   |

### Addresses

| Address     | Layer     |
| ----------- | --------- |
| MAC Address | Data Link |
| IP Address  | Network   |

### Protocols

| Protocol | Layer     |
| -------- | --------- |
| TCP      | Transport |
| UDP      | Transport |

### Data Units

| Layer     | Data Unit |
| --------- | --------- |
| Transport | Segment   |
| Network   | Packet    |
| Data Link | Frame     |
| Physical  | Bit       |

# Networking MCQs

## Section 2: IP Addressing, Subnetting, DHCP & DNS (Q26–Q50)

### Q26. What does IP stand for?

A. Internet Process

B. Internal Protocol

C. Internet Protocol

D. Internet Program

**Answer:** C

---

### Q27. Which version of IP uses 32-bit addressing?

A. IPv3

B. IPv4

C. IPv5

D. IPv6

**Answer:** B

---

### Q28. Which version of IP uses 128-bit addressing?

A. IPv4

B. IPv5

C. IPv6

D. IPv7

**Answer:** C

---

### Q29. How many octets are present in an IPv4 address?

A. 2

B. 4

C. 6

D. 8

**Answer:** B

---

### Q30. Which of the following is a valid IPv4 address?

A. 192.168.1.300

B. 192.168.1.10

C. 256.1.1.1

D. 192.168.-1.1

**Answer:** B

---

### Q31. Which of the following is a private Class A IP range?

A. 192.168.0.0 – 192.168.255.255

B. 172.16.0.0 – 172.31.255.255

C. 10.0.0.0 – 10.255.255.255

D. 127.0.0.0 – 127.255.255.255

**Answer:** C

---

### Q32. Which of the following is a private Class B IP range?

A. 172.16.0.0 – 172.31.255.255

B. 192.168.0.0 – 192.168.255.255

C. 10.0.0.0 – 10.255.255.255

D. 169.254.0.0 – 169.254.255.255

**Answer:** A

---

### Q33. Which of the following is a private Class C IP range?

A. 172.16.0.0 – 172.31.255.255

B. 192.168.0.0 – 192.168.255.255

C. 127.0.0.0 – 127.255.255.255

D. 169.254.0.0 – 169.254.255.255

**Answer:** B

---

### Q34. Which address is used for loopback testing?

A. 0.0.0.0

B. 255.255.255.255

C. 127.0.0.1

D. 192.168.1.1

**Answer:** C

---

### Q35. What is the primary purpose of a subnet mask?

A. Encrypt data

B. Identify network and host portions

C. Assign MAC addresses

D. Block traffic

**Answer:** B

---

### Q36. What is the subnet mask for a /24 network?

A. 255.0.0.0

B. 255.255.0.0

C. 255.255.255.0

D. 255.255.255.255

**Answer:** C

---

### Q37. What is the CIDR notation for 255.0.0.0?

A. /8

B. /16

C. /24

D. /32

**Answer:** A

---

### Q38. What is the CIDR notation for 255.255.0.0?

A. /8

B. /16

C. /24

D. /32

**Answer:** B

---

### Q39. What is the CIDR notation for 255.255.255.0?

A. /8

B. /16

C. /24

D. /32

**Answer:** C

---

### Q40. What does DHCP stand for?

A. Dynamic Host Configuration Protocol

B. Domain Host Control Protocol

C. Dynamic Hardware Configuration Protocol

D. Data Host Communication Protocol

**Answer:** A

---

### Q41. What is the primary purpose of DHCP?

A. Resolve domain names

B. Assign IP addresses automatically

C. Encrypt traffic

D. Route packets

**Answer:** B

---

### Q42. Which of the following is the correct DHCP process sequence?

A. Request → Offer → Discover → Acknowledge

B. Discover → Offer → Request → Acknowledge

C. Offer → Discover → Acknowledge → Request

D. Discover → Request → Offer → Acknowledge

**Answer:** B

---

### Q43. What does DNS stand for?

A. Domain Network Service

B. Data Naming System

C. Domain Name System

D. Dynamic Name Service

**Answer:** C

---

### Q44. What is the primary function of DNS?

A. Assign IP addresses

B. Convert domain names into IP addresses

C. Encrypt data

D. Manage routers

**Answer:** B

---

### Q45. Which DNS record maps a domain name to an IPv4 address?

A. MX

B. CNAME

C. AAAA

D. A

**Answer:** D

---

### Q46. Which DNS record maps a domain name to an IPv6 address?

A. A

B. MX

C. AAAA

D. NS

**Answer:** C

---

### Q47. Which DNS record is used for email routing?

A. MX

B. A

C. AAAA

D. PTR

**Answer:** A

---

### Q48. What is the default gateway?

A. Device that translates domain names

B. Device that forwards traffic to other networks

C. Device that assigns IP addresses

D. Device that stores webpages

**Answer:** B

---

### Q49. An IP address starting with 169.254.x.x generally indicates:

A. DNS issue

B. Gateway issue

C. DHCP failure

D. Router failure

**Answer:** C

---

### Q50. What is the broadcast address for the network 192.168.1.0/24?

A. 192.168.1.0

B. 192.168.1.1

C. 192.168.1.254

D. 192.168.1.255

**Answer:** D

---

# Quick Revision

### Private IP Ranges

| Class | Range                         |
| ----- | ----------------------------- |
| A     | 10.0.0.0 – 10.255.255.255     |
| B     | 172.16.0.0 – 172.31.255.255   |
| C     | 192.168.0.0 – 192.168.255.255 |

### Important Addresses

| Address         | Purpose   |
| --------------- | --------- |
| 127.0.0.1       | Loopback  |
| 169.254.x.x     | APIPA     |
| 255.255.255.255 | Broadcast |

### CIDR

| CIDR | Subnet Mask     |
| ---- | --------------- |
| /8   | 255.0.0.0       |
| /16  | 255.255.0.0     |
| /24  | 255.255.255.0   |
| /32  | 255.255.255.255 |

### DHCP

DORA:

* Discover
* Offer
* Request
* Acknowledge

# Networking MCQs

## Section 3: Protocols, Ports & Network Services (Q51–Q75)

### Q51. Which protocol is primarily used for browsing websites?

A. FTP

B. SMTP

C. HTTP

D. SNMP

**Answer:** C

---

### Q52. What is the default port number of HTTP?

A. 21

B. 22

C. 80

D. 443

**Answer:** C

---

### Q53. What is the default port number of HTTPS?

A. 22

B. 80

C. 110

D. 443

**Answer:** D

---

### Q54. What does HTTPS provide that HTTP does not?

A. Routing

B. Encryption

C. IP Addressing

D. DNS Resolution

**Answer:** B

---

### Q55. Which protocol is used for transferring files?

A. FTP

B. ICMP

C. ARP

D. DHCP

**Answer:** A

---

### Q56. What is the default port number of FTP?

A. 20 and 21

B. 22

C. 23

D. 25

**Answer:** A

---

### Q57. Which protocol is the secure version of FTP?

A. HTTP

B. SFTP

C. SMTP

D. Telnet

**Answer:** B

---

### Q58. Which protocol is used for secure remote login?

A. FTP

B. SSH

C. HTTP

D. SNMP

**Answer:** B

---

### Q59. What is the default port number of SSH?

A. 21

B. 22

C. 23

D. 25

**Answer:** B

---

### Q60. Which protocol is an insecure remote login protocol largely replaced by SSH?

A. SMTP

B. POP3

C. Telnet

D. IMAP

**Answer:** C

---

### Q61. What is the default port number of Telnet?

A. 21

B. 22

C. 23

D. 25

**Answer:** C

---

### Q62. Which protocol is primarily used for sending emails?

A. SMTP

B. POP3

C. IMAP

D. FTP

**Answer:** A

---

### Q63. What is the default port number of SMTP?

A. 25

B. 53

C. 80

D. 110

**Answer:** A

---

### Q64. Which protocol is used to download emails from a mail server?

A. HTTP

B. SMTP

C. POP3

D. DNS

**Answer:** C

---

### Q65. What is the default port number of POP3?

A. 25

B. 53

C. 110

D. 143

**Answer:** C

---

### Q66. Which protocol allows emails to remain on the server while accessing them?

A. POP3

B. IMAP

C. SMTP

D. FTP

**Answer:** B

---

### Q67. What is the default port number of IMAP?

A. 110

B. 143

C. 443

D. 587

**Answer:** B

---

### Q68. Which protocol converts domain names into IP addresses?

A. DHCP

B. DNS

C. FTP

D. ICMP

**Answer:** B

---

### Q69. What is the default port number used by DNS?

A. 25

B. 53

C. 67

D. 161

**Answer:** B

---

### Q70. Which protocol automatically assigns IP addresses?

A. DNS

B. ICMP

C. DHCP

D. ARP

**Answer:** C

---

### Q71. Which ports are used by DHCP?

A. 53 and 54

B. 67 and 68

C. 80 and 443

D. 110 and 143

**Answer:** B

---

### Q72. Which protocol is used by the ping command?

A. TCP

B. UDP

C. ICMP

D. ARP

**Answer:** C

---

### Q73. Which protocol converts an IP address into a MAC address?

A. DNS

B. DHCP

C. ARP

D. FTP

**Answer:** C

---

### Q74. What does SNMP stand for?

A. Secure Network Management Protocol

B. Simple Network Management Protocol

C. System Network Monitoring Protocol

D. Standard Network Message Protocol

**Answer:** B

---

### Q75. Which port is commonly associated with SNMP?

A. 53

B. 80

C. 161

D. 443

**Answer:** C

---

# High-Value Port Numbers

| Protocol | Port   |
| -------- | ------ |
| FTP      | 20, 21 |
| SSH      | 22     |
| Telnet   | 23     |
| SMTP     | 25     |
| DNS      | 53     |
| DHCP     | 67, 68 |
| HTTP     | 80     |
| POP3     | 110    |
| IMAP     | 143    |
| SNMP     | 161    |
| HTTPS    | 443    |

---

# Memory Tricks

### Secure Protocols

* HTTPS → 443
* SSH → 22
* SFTP → 22

---

### Email Protocols

* SMTP → Send Mail → 25
* POP3 → Download Mail → 110
* IMAP → Access Mail on Server → 143

---

### Network Services

* DNS → 53
* DHCP → 67,68
* SNMP → 161

---

# Most Asked TCS ITIS Questions

### Which protocol is used by ping?

**Answer:** ICMP

### Which protocol maps IP addresses to MAC addresses?

**Answer:** ARP

### Which protocol is used for secure remote login?

**Answer:** SSH

### Which protocol is used for email sending?

**Answer:** SMTP

### Which protocol is used for DNS resolution?

**Answer:** DNS

### Which protocol automatically assigns IP addresses?

**Answer:** DHCP

### What is the port number of HTTPS?

**Answer:** 443

### What is the port number of SSH?

**Answer:** 22

# Networking MCQs

## Section 4: Network Troubleshooting & Scenario-Based Questions (Q76–Q100)

### Q76. Which command is commonly used to test network connectivity?

A. netstat

B. ping

C. arp

D. route

**Answer:** B

---

### Q77. Which protocol does the ping command use?

A. TCP

B. UDP

C. ICMP

D. ARP

**Answer:** C

---

### Q78. Which command shows the path packets take to reach a destination?

A. nslookup

B. traceroute

C. ping

D. hostname

**Answer:** B

---

### Q79. What is the Windows equivalent of traceroute?

A. traceip

B. tracert

C. trace

D. route

**Answer:** B

---

### Q80. Which command displays IP configuration in Windows?

A. ifconfig

B. ip addr

C. ipconfig

D. netstat

**Answer:** C

---

### Q81. Which command displays detailed network information in Windows?

A. ipconfig /all

B. ipconfig /show

C. ipconfig /detail

D. netconfig

**Answer:** A

---

### Q82. Which command renews a DHCP-assigned IP address in Windows?

A. ipconfig /new

B. ipconfig /refresh

C. ipconfig /renew

D. ipconfig /restart

**Answer:** C

---

### Q83. Which command releases the current DHCP-assigned IP address?

A. ipconfig /remove

B. ipconfig /release

C. ipconfig /delete

D. ipconfig /stop

**Answer:** B

---

### Q84. Which command is the modern Linux replacement for ifconfig?

A. netstat

B. ip addr

C. route

D. ping

**Answer:** B

---

### Q85. Which command displays the hostname of a system?

A. whoami

B. hostname

C. netstat

D. host

**Answer:** B

---

### Q86. Which command is used to troubleshoot DNS resolution issues?

A. ping

B. nslookup

C. arp

D. route

**Answer:** B

---

### Q87. Which command displays active network connections?

A. nslookup

B. ping

C. netstat

D. arp

**Answer:** C

---

### Q88. Which Linux command is commonly used as a modern replacement for netstat?

A. ss

B. curl

C. wget

D. top

**Answer:** A

---

### Q89. Which command displays the ARP table?

A. route

B. arp -a

C. ping

D. nslookup

**Answer:** B

---

### Q90. Which command displays the routing table in Linux?

A. ping

B. hostname

C. ip route

D. nslookup

**Answer:** C

---

### Q91. Which command is commonly used to test APIs and websites?

A. arp

B. curl

C. route

D. traceroute

**Answer:** B

---

### Q92. Which command is commonly used to download files from the internet in Linux?

A. curl

B. wget

C. ping

D. arp

**Answer:** B

---

### Q93. A system receives an IP address of 169.254.10.20. What is the most likely issue?

A. DNS failure

B. Router failure

C. DHCP failure

D. Switch failure

**Answer:** C

---

### Q94. A user can ping an IP address but cannot access a website using its domain name. What is the likely issue?

A. DHCP

B. DNS

C. Router

D. Switch

**Answer:** B

---

### Q95. Which command would you use first to verify connectivity to a server?

A. ping

B. arp

C. route

D. netstat

**Answer:** A

---

### Q96. A website is slow to load. Which command helps identify where delays occur along the network path?

A. arp

B. hostname

C. traceroute

D. ipconfig

**Answer:** C

---

### Q97. Which command can help verify whether a domain name resolves to an IP address?

A. ping

B. route

C. nslookup

D. arp

**Answer:** C

---

### Q98. A user reports no internet access. Which should be checked first?

A. Application logs

B. Physical connectivity (cables/Wi-Fi)

C. DNS records

D. Firewall rules

**Answer:** B

---

### Q99. Which command displays both listening ports and established connections?

A. netstat

B. ping

C. arp

D. hostname

**Answer:** A

---

### Q100. Which troubleshooting model is generally recommended?

A. Restart everything immediately

B. Check physical layer first, then move upward

C. Reinstall the operating system

D. Replace the router first

**Answer:** B

---

# Quick Revision

## Connectivity Commands

| Command              | Purpose           |
| -------------------- | ----------------- |
| ping                 | Test Connectivity |
| traceroute / tracert | Trace Route       |
| nslookup             | DNS Lookup        |
| hostname             | Show Hostname     |

---

## IP Configuration Commands

| OS           | Command  |
| ------------ | -------- |
| Windows      | ipconfig |
| Linux        | ip addr  |
| Legacy Linux | ifconfig |

---

## Monitoring Commands

| Command  | Purpose            |
| -------- | ------------------ |
| netstat  | Active Connections |
| ss       | Socket Statistics  |
| arp -a   | ARP Table          |
| ip route | Routing Table      |

---

## Web & Download Commands

| Command | Purpose            |
| ------- | ------------------ |
| curl    | Test Websites/APIs |
| wget    | Download Files     |

---

# Scenario-Based Questions Summary

### 169.254.x.x Address

**Cause:** DHCP Failure

---

### Can Ping IP But Not Domain

**Cause:** DNS Issue

---

### No Internet Access

**Check First:** Physical Connectivity

---

### Network Path Analysis

**Command:** traceroute / tracert

---

### Verify DNS Resolution

**Command:** nslookup

---

# Networking MCQ Bank Completed

✅ 100 MCQs

✅ Networking Fundamentals

✅ OSI Model

✅ TCP/IP Model

✅ IPv4 & IPv6

✅ Public & Private IPs

✅ DHCP

✅ DNS

✅ Subnetting Basics

✅ Ports & Protocols

✅ Email Protocols

✅ ARP & ICMP

✅ Networking Commands

✅ Troubleshooting

✅ Scenario-Based Questions

---

# Important Ports (Must Memorize)

| Protocol | Port  |
| -------- | ----- |
| FTP      | 20,21 |
| SSH      | 22    |
| Telnet   | 23    |
| SMTP     | 25    |
| DNS      | 53    |
| DHCP     | 67,68 |
| HTTP     | 80    |
| POP3     | 110   |
| IMAP     | 143   |
| SNMP     | 161   |
| HTTPS    | 443   |
