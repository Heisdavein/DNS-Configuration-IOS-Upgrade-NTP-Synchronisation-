# Cisco Networking Homelab

### Building Enterprise Networking Skills Through Hands-On Practice

> *"Reading about networking teaches the concepts. Building a network teaches the lessons."*

This repository documents my hands-on Cisco networking homelab built in **Cisco Packet Tracer**, where I configured and explored three essential enterprise networking services:

* 🌐 Domain Name System (DNS)
* 🔄 Cisco IOS Upgrade using TFTP
* 🕒 Network Time Protocol (NTP)

Rather than following labs mechanically, I focused on understanding **why** each technology exists, **how** it works behind the scenes, and **what** happens when things go wrong. Every configuration was built, tested, verified, and documented to deepen my understanding of enterprise networking.

---

# Why I Built This Project

Networking is the backbone of every IT environment.

Whether users are browsing the web, accessing company resources, authenticating to servers, or connecting to cloud services, none of it works without a reliable network.

As I progressed through my IT Support and Cybersecurity journey, I realised that understanding operating systems alone wasn't enough. To troubleshoot infrastructure effectively, I needed to understand the services that keep networks running.

Instead of relying solely on theory, I wanted practical experience.

I wanted to:

* Build networks from scratch
* Configure routers and switches
* Deploy core network services
* Break configurations
* Troubleshoot failures
* Understand why every command matters

This homelab is the result of that journey.

---

# Project Objectives

The primary goal of this project was to strengthen my practical networking skills by implementing fundamental enterprise services in a simulated environment.

Specifically, I wanted to:

* Configure internal DNS services
* Upgrade Cisco IOS using TFTP
* Configure Network Time Protocol (NTP)
* Improve Cisco IOS CLI proficiency
* Develop structured troubleshooting habits
* Document each lab professionally
* Understand the operational considerations behind enterprise networking

---

# Technologies Used

| Category       | Technologies                                                         |
| -------------- | -------------------------------------------------------------------- |
| Simulation     | Cisco Packet Tracer                                                  |
| Networking     | TCP/IP, DNS, DHCP, TFTP, NTP                                         |
| Devices        | Cisco Routers, Cisco Switches                                        |
| Administration | Cisco IOS CLI                                                        |
| Concepts       | Routing, Switching, Infrastructure Services, Network Troubleshooting |

---

# Labs Included

## 🌐 DNS Configuration

Configured an internal DNS server capable of resolving hostnames for devices across the LAN.

### Topics Covered

* Static IP addressing
* DNS Records
* Name Resolution
* DHCP Integration
* Hostname Testing
* Web Server Access
* Ping by Hostname
* DNS Troubleshooting

---

## 🔄 Cisco IOS Upgrade using TFTP

Performed a complete Cisco IOS upgrade while following maintenance best practices.

### Topics Covered

* Verifying IOS Version
* Flash Storage Management
* IOS Image Removal
* TFTP File Transfer
* Configuration Backup
* Router Reload
* Upgrade Verification
* Failure Scenarios
* Risk Assessment

---

## 🕒 Network Time Protocol (NTP)

Configured centralized time synchronization across network devices.

### Topics Covered

* NTP Configuration
* Time Synchronisation
* Authentication
* Clock Verification
* Event Correlation
* Security Considerations
* Log Accuracy

---

# Skills Demonstrated

This project demonstrates practical experience with:

* Cisco Router Configuration
* Cisco Switch Configuration
* Cisco IOS CLI
* Enterprise DNS
* TFTP Operations
* Router Maintenance
* NTP Configuration
* Infrastructure Documentation
* Network Troubleshooting
* Critical Thinking
* Technical Writing

---

# What I Learned

This project fundamentally changed the way I think about networking.

Some of my biggest takeaways include:

* DNS translates names—it doesn't carry network traffic.
* Infrastructure changes require planning, verification, and rollback strategies.
* Time synchronization is critical for security, authentication, and logging.
* Networking isn't a collection of isolated protocols—it's an ecosystem where every service depends on another.
* The best troubleshooting starts with understanding dependencies rather than memorizing commands.

Most importantly, I learned that confidence comes from **building**, **breaking**, **fixing**, and **understanding** systems—not simply reading about them.

---

# Repository Structure

```text
Cisco-Networking-Homelab/
│
├── README.md
├── Homelab Documentation.pdf
├── Packet Tracer Files/
│   ├── DNS Lab.pkt
│   ├── IOS Upgrade Lab.pkt
│   └── NTP Lab.pkt
│
├── Images/
│   ├── Network Topology.png
│   ├── DNS Configuration.png
│   ├── IOS Upgrade.png
│   └── NTP Configuration.png
│
└── LICENSE
```

---

# Why This Repository Is Different

This isn't simply a collection of Packet Tracer files.

Every lab includes:

* The reasoning behind each configuration
* Step-by-step implementation
* Command explanations
* Validation procedures
* Troubleshooting methodology
* Reflection on lessons learned
* Real-world enterprise context

My goal wasn't just to complete networking labs—it was to understand the technologies deeply enough to explain them to someone else.

---

# Future Roadmap

This homelab is only the beginning.

Future additions will include:

* OSPF
* VLANs
* Inter-VLAN Routing
* EtherChannel
* Access Control Lists (ACLs)
* NAT & PAT
* Syslog
* SNMP
* SSH Device Management
* Port Security
* DHCP Snooping
* STP Optimisation
* Network Automation

---

# About Me

I'm **Clinton Kehinde**, an IT Support professional.

I enjoy building homelabs that transform theory into practical skills while documenting everything I learn along the way.

This repository reflects my commitment to continuous learning, hands-on practice, and developing production-ready technical skills.

---

