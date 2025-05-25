## **Web Security (4 Hours)**

---

### **1. Threats (1L)**

#### **Malicious Code**

* **Viruses**

  * Attaches to host files or programs.
  * Requires user action to spread.
* **Worms**

  * Self-replicating.
  * Spreads through networks automatically.
* **Trojan Horses**

  * Disguised as legitimate software.
  * Does not replicate, but enables unauthorized access or damage.

#### **Eavesdropping**

* Unauthorized interception of data during transmission.
* Example: packet sniffing on unsecured networks.
* Prevention: Encryption (e.g., SSL/TLS, VPN).

#### **Spoofing**

* Impersonating another entity to gain unauthorized access.
* Types:

  * IP Spoofing: Using a forged IP address.
  * Email Spoofing: Faking sender’s address.
  * DNS Spoofing: Redirecting traffic to malicious sites.

#### **Modification**

* Unauthorized alteration of data.
* Example: modifying financial records or website content in transit.

#### **Denial of Service (DoS) Attacks**

* Flooding a target system with traffic to make it unavailable.
* **Distributed DoS (DDoS)**: Attacks launched from multiple systems.

---

### **2. Network Security Techniques (2L)**

#### **Password and Authentication**

* **Password-Based**: Basic authentication using credentials.
* **Multifactor Authentication (MFA)**:

  * Something you know (password)
  * Something you have (token)
  * Something you are (biometric)
* **Authentication Protocols**:

  * Basic Auth (HTTP), Digest Auth, OAuth, OpenID, Kerberos

#### **Virtual Private Network (VPN)**

* Encrypts data traffic between user and server.
* Provides secure remote access.
* Tunneling protocols: PPTP, L2TP, IPSec.

#### **IP Security (IPSec)**

* Protocol suite for securing IP communications.
* Operates at Network Layer.
* Provides:

  * **Authentication Header (AH)** – data integrity and origin.
  * **Encapsulating Security Payload (ESP)** – confidentiality, integrity.

#### **Security in Electronic Transactions**

* Key concepts: confidentiality, integrity, authentication, non-repudiation.
* Mechanisms:

  * **Digital Signatures**: verifies sender identity.
  * **Digital Certificates**: used with PKI for trust verification.
  * **SSL/TLS**: encrypts online transactions (e.g., HTTPS).
  * **Payment Gateways**: intermediaries in e-commerce.

#### **Secure Socket Layer (SSL) / Transport Layer Security (TLS)**

* Protocols for secure communication over the internet.
* Provides encryption, integrity, and authentication.
* TLS is the modern, secure replacement for SSL.

#### **Secure Shell (SSH)**

* Protocol for secure command-line and remote login.
* Encrypts all data exchanged over the network.
* Uses public-key or password-based authentication.

---

### **3. Firewall (1L)**

#### **Introduction**

* A system designed to prevent unauthorized access to or from a private network.
* Acts as a barrier between trusted and untrusted networks.

#### **Packet Filtering**

* Filters packets based on source/destination IP, port, and protocol.
* Stateless – each packet is checked independently.

#### **Stateful Inspection**

* Tracks connection state.
* Makes decisions based on context (e.g., part of a valid session).

#### **Application Layer Filtering**

* Filters based on application data (e.g., HTTP, FTP).
* Can detect and block application-level threats.

#### **Proxy Firewalls**

* Intermediary between client and server.
* Hides internal network structure.
* Can cache content and filter by user, content, or URL.

---

## **Summary Table**

| Section              | Topics                                                              |
| -------------------- | ------------------------------------------------------------------- |
| **Threats**          | Viruses, Worms, Trojans, Eavesdropping, Spoofing, Modification, DoS |
| **Network Security** | Authentication, VPN, IPSec, Secure Transactions, SSL, SSH           |
| **Firewall**         | Packet Filtering, Stateful Inspection, Application Layer, Proxy     |

---
