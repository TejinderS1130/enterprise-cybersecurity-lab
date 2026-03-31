#  Environment Setup & Lab Infrastructure

## Objective

Establish a controlled virtual lab environment to simulate real-world cybersecurity scenarios, including offensive testing and SOC monitoring.

---

## Overview

A multi-system virtual environment was deployed consisting of:

*  Kali Linux (Attacker Machine)
*  Windows 10 (Target / Monitoring System)
*  Internal Virtual Network

This setup enables safe execution of:

* Network scanning
* Vulnerability assessment
* Exploitation
* Detection engineering

---

#  Kali Linux Setup

##  Deployment

Kali Linux was installed and configured as the primary attacker machine within a virtualized environment.

---

## Kali Linux Environment

![Kali Desktop](../screenshots/kali-desktop.png)

**Kali Linux VM successfully deployed and configured for offensive security operations**

---

## System Validation

Basic Linux commands were executed to verify system integrity and configuration.

![Kali Terminal](../screenshots/kali-terminal.png)

**System validation performed using core Linux commands (`uname`, `date`, etc.) confirming proper configuration**

---

## Snapshot Management

A snapshot was created to preserve the system state, enabling rollback during testing scenarios.

![Kali Snapshot](../screenshots/kali-snapshot.png)

**Virtual machine snapshot created to maintain a stable and repeatable testing environment**

---

# Windows 10 Setup

## Deployment

A Windows 10 virtual machine was deployed to simulate a target system and support security monitoring tools.

---

## Security Tool Installation

Wireshark was installed to enable network traffic analysis and packet inspection.

![Wireshark](../screenshots/windows-wireshark.png)

**Wireshark installed and configured for network traffic monitoring and analysis**

---

## Snapshot Management

A snapshot was taken to preserve the system configuration before conducting further testing.

![Windows Snapshot](../screenshots/windows-snapshot.png)

**Windows VM snapshot created to ensure system stability and recovery capability**

---

#  Security Relevance

This environment forms the foundation for all subsequent phases:

*  Reconnaissance
*  Network scanning
*  Vulnerability assessment
*  Exploitation
*  SOC detection

---
