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
| Internet Protocol version 4 (IPv4) | Most widely used protocol for addressing devices on a network |
| Internet Protocol version 6 (IPv6) | Successor to IPv4, designed to solve address exhaustion |

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

The layers are as follows:

**1. Application Layer (Layer 4):**
- Handles high-level protocols.
- HTTP, FTP, SMTP, DNS

**2. Transport Layer (Layer 3):**
- Manages end-to-end communication.
- TCP for reliability, UDP for speed

**3. Internet Layer (Layer 2):**
- Handles addressing, routing and packet forwarding
- IP, ICMP

**4. Network Access Layer (Layer 1):**
- Defines physical transmission
- Ethernet, Wi-Fi, ARP, MAC addressing

### OSI & TCP/IP - Comparison:

#### Similarities:

- Both layered models for network communication.
- Use encapsulation and de-capsulation.

#### Differences:

- TCP/IP is more practical and widely used.
- OSI more theoretical.
- TCP/IP combines the __presentation__ and __session__ layers into __application__ layer.

### IPv4 (Internet Protocol version 4)

- Addresses are written in dotted decimal format (e.g. 192.168.1.1).
- Connectionless and operates at the **Network Layer (Layer 3)** of the OSI model.

#### IPv4 Classes

| Class | First Octet Range | Max No. of Hosts Per Network | No. of Networks |
| ----- | ----------------- | ---------------------------- | --------------- |
| A | 1 - 126 | 16,777,214 | 128 (excluding 0 and 127) |
| B | 128 - 191 | 65,534 | 16,384 |
| C | 192 - 223 | 254 | 2,097,152 |
| D | 224 - 239 | N/A (Multicast) | N/A |
| E | 240 - 255 | N/A (Reserved) | N/A |

#### Limitations

- 32-bit address space allows for ~ 4.3 billion addresses (not enough for growing number of devices).
- **NAT (Network Address Translation)** - allows multiple devices to share a single public IP.
- **CIDR (Classless Inter-Domain Routing)** - efficient allocation of IP addresses.
- **IPv6 Adoption** - the next-gen protocol that has a 128-bit address space.

### IPv6 (Internet Protocol version 6)

- Uses **128-bit addressing scheme**, allows for **340 undecillion unique addresses**.
- Written in **hexadecimal format** (e.g. 2001:0db8:85a3::85a3::8a2e:0370:7334).
- Connectionless and operates at the **Network Layer (Layer 3)** of the OSI model.

#### Benefits

- No NAT needed.
- **Built-in security:** IPSec is mandatory for IPv6.
- **Auto-configuration**
- Better multicase and anycast capabilities.

#### Challenges

- **Compatability issues** with older IPv4 networks.
- **Slow transition** due to infrastructure upgrades.

### Wi-Fi

- Wireless networking technology which allows devices to connect to the internet without physical cables.
- Operates under the **IEEE 802.11** standard.

#### Wi-Fi Security Measures:

- **WEP (Weak), WPA, WPA2, WPA3**: Encryption for secure connections.
- **MAC Filtering**: Restricts devices based on MAC addresses.
- **SSID Hiding**: Conceals network name from public visibility.
