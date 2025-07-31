# DOMAIN 5: Security Operations

## 📖 Overview
> Sections in this domain:

1. Data Security
2. System Hardening
3. Best Practice Security Policies
4. Security Awareness Training

---

## 🔑 Key Concepts

- Incident Response (IR) Process
- Encryption Methods
- Logging and Monitoring
- Patch and Vulnerability Management
- Malware Prevention and Detection
- Security Awareness Training
- Configuration
- Best Practice Policies

---

## 📌 Definitions

| Term | Definition |
|------|------------|
| SIEM | Security Information and Event Management system |
| SOC | Security Operations Center — central unit for security monitoring |
| IR | The process for detecting, responding to, and recovering from incidents |
| Encryption | Process of converting plaintext into ciphertext to protect data |
| Full Disk Encryption (FDE) | Encrypts entire contents of storage device |
| Self-Encrypting Drive (SED) | Hardware-based encryption method - drive automatically encrypts and decrypts data |
| Cloud Storage Encryption | Encrypts data stored in the cloud |
| Transparent Data Encryption (TDE) | Encrypts database files automatically at the storage level |
| Secure Sockets Layer (SSL) | Encrypts data transmitted between a user's device and a server |
| Hypertext Transfer Protocol Secure (HTTPS) | Secure version of HTTP that uses SSL/TLS to encrypt web traffic |
| Symmetric Encryption | Uses the same key (shared secret) for both encryption and decryption |
| Asymmetric Encryption | Uses a pair of keys - public & private key pair |
| Trusted Platform Module (TPM) | Dedicated microchip designed to secure hardware by storing cryptographic keys and other sensitive data |

---

## 🧠 Exam Tips

- 🔸 Memorize the **incident response lifecycle** (Preparation, Detection, Response, Recovery, Lessons Learned)
- 🔸 Know common **malware types** (virus, worm, trojan, ransomware)
- 🔸 Understand **security roles and responsibilities** (user, admin, analyst)

---

## 📝 Notes
> General notes and diagrams will be found here.

### Encrpytion

- Used to ensure **confidentiality**, **integrity** and **authenticity** of information.

#### Key Components:

- **Algorithm** (e.g. AES, RSA)
- **Encryption Key** (public/private or symmetric)

#### Types:

- **Symmetric** (single key)
- **Asymmetric** (public-private key pair)

### Data Protection in Transit:

- **SSL (Secure Sockets Layer):**

Encrypts data transmitted between a user's device and a server. This prevents unauthorised access or interception during transit.

- **HTTPS:**

Ensures communication between a browser and a website remains secure.

### Protection of Data in Use

- This refers to the safeguarding of data while it is being actively accessed, processed, or used in memory.
- Critical as data is typically decrypted during this stage, making it vulnerable to attacks.

### Symmetric vs. Asymmetric Encryption

| Symmetric | Asymmetric |
| --------- | ---------- |
| Fast and efficient | Slower compared to symmetric |
| Less scalable | Supports scalability and key distribution |
| Requiring secure key sharing | Secure key exchange but being slower |
| E.g. AES (Advanced Encryption Standard) | E.g. RSA (Rivest-Shamir Adleman |

### Block Ciphers

- Encrypts data in fixed-size blocks.
- Processes plaintext in chunks, applying the same encryption algorithm to each block.
- Slower but more secure for bulk data encryption.

### Stream Ciphers

- Encrypts the data one bit or byte at a time, continuously.
- Faster and more efficient for real-time applications.
- Often used in applications requiring high-speed encryption.
