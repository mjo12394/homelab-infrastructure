# Homelab Infrastructure

A hands-on IT infrastructure lab used to develop and document practical skills in networking, systems administration, virtualization, troubleshooting, automation, and mission-critical IT operations.

> **Security note:** All content in this public repository is sanitized. Credentials, secrets, sensitive addressing, internal configurations, and other private infrastructure details are excluded or replaced with safe examples.

## Purpose

This lab is designed to turn infrastructure concepts into practical experience through a repeatable cycle:

**Learn → Build → Break → Troubleshoot → Document → Improve**

The goal is to build demonstrable experience relevant to IT Operations, Network Operations, Systems Administration, and Data Center / Infrastructure roles.

## Current Architecture

Current high-level environment:

```text
Internet
   |
   v
Eero Network
   |
   v
UniFi Cloud Gateway Max
   |
   +-- Gaming PC
   |
   +-- Proxmox Server
```

Detailed addressing, firewall configuration, and other sensitive implementation details are maintained privately.

## Technologies

### Currently in use
- UniFi Cloud Gateway Max
- Proxmox Virtual Environment (VE)
- Linux
- Windows and macOS endpoints
- TCP/IP (Transmission Control Protocol/Internet Protocol) networking
- Firewall and network segmentation concepts
- Virtual machines

### Planned / expanding
- VLAN (Virtual Local Area Network) segmentation
- Windows Server
- Active Directory Domain Services (AD DS)
- Domain Name System (DNS)
- Dynamic Host Configuration Protocol (DHCP)
- Group Policy
- Network monitoring
- PowerShell automation
- Bash scripting
- Packet capture and network troubleshooting

## Planned Labs and Projects

- Document the current-state network
- Design and implement segmented VLANs
- Create firewall rules between trusted and isolated networks
- Deploy Windows Server and Active Directory Domain Services (AD DS)
- Configure Domain Name System (DNS) and Dynamic Host Configuration Protocol (DHCP)
- Build Linux server workloads in Proxmox
- Practice network and systems failure scenarios
- Document incident troubleshooting and root-cause analysis
- Create reusable PowerShell and Bash troubleshooting tools
- Build Standard Operating Procedures (SOPs) for common infrastructure tasks

## What I'm Learning

This repository documents my progression in:

- Enterprise networking fundamentals
- Network segmentation and access control
- Linux and Windows systems administration
- Virtualization
- Infrastructure troubleshooting
- Incident response and root-cause analysis
- Technical documentation
- IT automation
- Operational reliability

## Repository Approach

Public documentation focuses on architecture, methodology, sanitized examples, lessons learned, and completed projects. Sensitive or environment-specific material remains in a separate private repository.
