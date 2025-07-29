# DOMAIN 4: Network Security

## 📖 Overview
> Sections in this domain:

1. Computer Networking
2. Network Threats and Attacks
3. Network Security Infrastructure

---

## 🔑 Key Concepts

- Firewalls, Routers, Switches
- Threat Types
- Networks (OSI model, TCP/IP, IPv4, IPv6, Wi-Fi)
- Ports and Applications
- IDS/IPS (Intrusion Detection/Prevention Systems)
- VPNs and Secure Protocols
- Network Segmentation and DMZ
- IP Addressing and Subnetting Basics
- Cloud

---

## 📌 Definitions

| Term | Definition |
|------|------------|
| Intrusion Detection System (IDS) | Monitors for malicious activity |
| Virtual Private Network (VPN) | Creates an encrypted tunnel between networks or devices |
| Demilitarised Zone (DMZ) | A buffer zone between internal and external networks |
| Open Systems Interconnection (OSI) Model | Framework that standardises network communication |
| Transmission Control Protocol (TCP) / Internet Protocol (IP) Model | Foundtaional framework for the internet and modern networking |

---

## 🧠 Exam Tips

- 🔸 Understand **OSI vs TCP/IP models**
- 🔸 Know which **protocols are secure vs insecure** (e.g. HTTPS vs HTTP)
- 🔸 Recognize common **network threats** like MITM or DDoS

---

## 📝 Notes
> General notes and diagrams will be found here.

### Open Systems Interconnection (OSI) Model

- Standardises network communication.
- Ensures interoperability between different devices and systems.
- Simplifies the troubleshooting process by isolating issues to specific layers.

There are 7 layers, as follows:

#### **1. Application Layer (Layer 7):**
- Interfaces with applications.
- E.g. HTTP, FTP, SMTP)

#### **2. Presentation Layer (Layer 6):**
- Data formatting, encryption, compression.
- JPEG, MPEG, SSL/TLS

#### **3. Session Layer (Layer 5):**
- Manages sessions and connections.
- NetBIOS, PRC

#### **4. Transport Layer (Layer 4):**
- Ensures reliable transmission.
- TCP/UDP

#### **5. Network Layer (Layer 3):**
- Routing and addressing.
- IP, ICMP, Routers

#### **6. Data Link Layer (Layer 2):**
- Error detection and MAC addressing.
- Ethernet, MAC, Switches

#### **7. Physical Layer (Layer 1):**
- Transmission of raw bits.
- Cables, Wireless signals, Hubs, Repeaters

### TCP / IP Model

- Developed by US Department of Defence to ensure reliable communication.
- There are 4 layers which map closely to the OSI model.
- Was designed to standardise end-to-end communication across interconnected networks.
