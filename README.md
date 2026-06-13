# ApexPlanet Software Pvt. Ltd.
# Cybersecurity Internship - Task 1

## Foundation & Environment Setup

---

# Project Overview

This repository contains the work completed for Task 1 of the ApexPlanet Cybersecurity Internship Program.

The objective of this task was to set up a cybersecurity lab environment using Kali Linux, practice Linux fundamentals, understand networking concepts, and gain hands-on experience with common cybersecurity tools.

---

# Lab Environment

## Virtualization Platform
VMware Workstation

## Operating System
Kali Linux

## Vulnerable Web Application
DVWA (Damn Vulnerable Web Application)

## Security Tools Used

- Wireshark
- Nmap
- Netcat
- Linux Terminal

---

# Linux Fundamentals

## Current Working Directory

Command:

```bash
pwd
```

Purpose:
Displays the current working directory.

Screenshot:
03-pwd.jpeg

---

## List Files and Directories

Command:

```bash
ls
```

Purpose:
Lists files and directories available in the current location.

Screenshot:
04-ls.jpeg

---

## Change Directory

Command:

```bash
cd
```

Purpose:
Used to navigate between directories.

Screenshot:
05-cd.jpeg

---

## Change Permissions

Command:

```bash
chmod 777 test
```

Purpose:
Changes permissions of files and folders.

Screenshot:
06-chmod.jpeg

---

## Package Management

Command:

```bash
apt update
```

Purpose:
Updates package information and repositories.

Screenshot:
07-apt.jpeg

---

# Networking Fundamentals

## Network Configuration

Command:

```bash
ifconfig
```

Purpose:
Displays network interface and IP configuration details.

Screenshot:
08-ifconfig.jpeg

---

## Connectivity Testing

Command:

```bash
ping google.com
```

Purpose:
Tests connectivity with a remote server.

Screenshot:
09-ping.jpeg

---

## Active Connections

Command:

```bash
netstat -tuln
```

Purpose:
Displays active ports and network connections.

Screenshot:
10-netstat.jpeg

---

# DVWA Setup

DVWA (Damn Vulnerable Web Application) was successfully configured and tested.

Purpose:

- Learn web application security concepts.
- Understand common vulnerabilities.
- Create a safe testing environment.

Screenshot:
02-DVWA.jpeg

---

# Wireshark Analysis

## Tool

Wireshark

## Activity Performed

- Started packet capture.
- Generated network traffic.
- Applied DNS filters.
- Observed DNS requests and responses.

## Result

Successfully captured and analyzed network packets.

Screenshot:
11-Wireshark.jpeg

---

# Nmap Scanning

## Command

```bash
nmap localhost
```

## Purpose

- Discover open ports.
- Identify running services.
- Learn reconnaissance techniques.

## Result

Successfully scanned the target system and identified active services.

Screenshot:
12-Nmap.jpeg

---

# Netcat Communication

## Listener

```bash
nc -lvp 4444
```

## Client

```bash
nc 127.0.0.1 4444
```

## Purpose

- Test TCP communication.
- Understand client-server interaction.
- Verify connectivity.

## Result

Successfully exchanged messages between two terminals.

Screenshots:

- 13-Netcat.jpeg
- 14-Netcat.jpeg

---

# Screenshots Included

1. Kali Linux Desktop
2. DVWA Setup
3. pwd Command
4. ls Command
5. cd Command
6. chmod Command
7. apt Command
8. ifconfig Command
9. ping Command
10. netstat Command
11. Wireshark Capture
12. Nmap Scan
13. Netcat Communication
14. Netcat Communication

---

# Skills Acquired

- Linux Fundamentals
- VMware Virtualization
- Networking Basics
- Packet Analysis
- Port Scanning
- Network Reconnaissance
- Client-Server Communication
- Cybersecurity Lab Setup

---

# Conclusion

Successfully completed the Foundation & Environment Setup task by configuring a Kali Linux environment in VMware, deploying DVWA, practicing Linux commands, performing packet analysis with Wireshark, conducting network scans using Nmap, and testing communication using Netcat.

This task provided practical exposure to essential cybersecurity tools and concepts used in real-world environments.

---

# Author

Sameer Singh

ApexPlanet Cybersecurity Internship