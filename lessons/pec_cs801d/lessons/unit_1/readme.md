## **Introduction (6 Hours)**

---

### **1. Overview: Network of Networks, Intranet, Extranet, and Internet**

| Concept                 | Description                                                                                                           |
| ----------------------- | --------------------------------------------------------------------------------------------------------------------- |
| **Network of Networks** | The Internet is a global interconnection of millions of private, public, academic, business, and government networks. |
| **Intranet**            | Private network within an organization using Internet technologies (TCP/IP) for internal communication.               |
| **Extranet**            | Extended Intranet that allows controlled access to external partners, vendors, or customers.                          |
| **Internet**            | A global system of interconnected computer networks using the TCP/IP protocol suite.                                  |
| **Interoperability**    | The ability of systems from different vendors to communicate effectively across the Internet.                         |

---

### **2. World Wide Web (WWW)**

| Subtopic                               | Description                                                                            |
| -------------------------------------- | -------------------------------------------------------------------------------------- |
| **Domain**                             | The human-readable name of an IP address (e.g., `openai.com`).                         |
| **Subdomain**                          | A domain that is part of a larger domain (e.g., `chat.openai.com`).                    |
| **Address Resolution**                 | The process of converting domain names into IP addresses using DNS.                    |
| **DNS (Domain Name System)**           | A hierarchical, distributed database that maps domain names to IP addresses.           |
| **Telnet**                             | A protocol used for command-line remote login, now mostly replaced by SSH.             |
| **FTP (File Transfer Protocol)**       | Used to transfer files between client and server.                                      |
| **HTTP (HyperText Transfer Protocol)** | The protocol for transferring hypermedia documents, forming the foundation of the web. |

#### Additional Concepts:

* **URL vs URI**: URL (Uniform Resource Locator) is a specific type of URI that provides the means to access a resource.
* **HTTPS**: Secure version of HTTP, uses SSL/TLS for encryption.

---

### **3. Review of TCP/IP**

| Subtopic                  | Description                                                                       |
| ------------------------- | --------------------------------------------------------------------------------- |
| **Features**              | Layered architecture, scalability, reliable delivery, end-to-end communication.   |
| **TCP Segment**           | Includes source/destination ports, sequence/ack numbers, flags, checksum, etc.    |
| **Three-Way Handshaking** | TCP connection setup: SYN → SYN-ACK → ACK.                                        |
| **Flow Control**          | Managed using the **Window Size** in TCP to avoid overwhelming the receiver.      |
| **Error Control**         | TCP uses checksums and retransmissions (ARQ mechanisms) for error handling.       |
| **Congestion Control**    | Algorithms like Slow Start, Congestion Avoidance, Fast Retransmit, Fast Recovery. |
| **IP Datagram**           | Basic unit of data transmitted over IP. Contains header and payload.              |
| **IPv4**                  | 32-bit address, uses dotted decimal notation.                                     |
| **IPv6**                  | 128-bit address, supports a larger address space and built-in security.           |

#### Additional TCP/IP Concepts:

* **Ports and Sockets**
* **Encapsulation and Decapsulation**
* **Protocol Stack Layers (Link, Internet, Transport, Application)**

---

### **4. IP Subnetting and Addressing**

| Subtopic                              | Description                                                                 |
| ------------------------------------- | --------------------------------------------------------------------------- |
| **Classful Addressing**               | Divides IP addresses into A, B, C, D, E based on fixed boundary (obsolete). |
| **Classless Addressing (CIDR)**       | Allows flexible subnetting using subnet masks (e.g., `/24`).                |
| **Subnetting**                        | Dividing a network into smaller subnets using subnet masks.                 |
| **NAT (Network Address Translation)** | Translates private IP addresses to a public IP address.                     |
| **IP Masquerading**                   | A form of NAT where multiple internal hosts appear as one public IP.        |
| **IP Tables**                         | Linux utility for configuring packet filtering and NAT rules.               |

#### Related Topics:

* **Private vs Public IP Ranges**
* **Binary Math for Subnetting**
* **Subnet Masks and Wildcard Masks**

---

### **5. Internet Routing Protocol**

| Subtopic                 | Description                                                           |
| ------------------------ | --------------------------------------------------------------------- |
| **Intra-Domain Routing** | Routing within a single organization or AS (e.g., RIP, OSPF, EIGRP).  |
| **Inter-Domain Routing** | Routing between autonomous systems (e.g., BGP).                       |
| **Unicast Routing**      | One-to-one transmission from one sender to one receiver.              |
| **Multicast Routing**    | One-to-many transmission, only to interested receivers (e.g., PIM).   |
| **Broadcast Routing**    | One-to-all transmission within a local network (e.g., ARP broadcast). |

#### Other Routing Concepts:

* **Routing Table**
* **Metrics and Cost**
* **Distance Vector vs Link State Protocols**
* **Default and Static Routes**

---

### **6. Electronic Mail (E-mail)**

| Subtopic                                 | Description                                                                         |
| ---------------------------------------- | ----------------------------------------------------------------------------------- |
| **POP3 (Post Office Protocol v3)**       | Retrieves emails from server to client and deletes them from the server by default. |
| **SMTP (Simple Mail Transfer Protocol)** | Used to send emails between servers and from client to server.                      |

#### Additional Email Concepts:

* **IMAP (Internet Message Access Protocol)**: Allows email access without removing from the server.
* **Email Header and MIME Types**
* **Mail Server and Mail Client**
* **Email Security (SPF, DKIM, DMARC)**

---

## Summary Table

| Main Topic    | Covered Subtopics                                                                    |
| ------------- | ------------------------------------------------------------------------------------ |
| Overview      | Network of Networks, Intranet, Extranet, Internet                                    |
| WWW           | Domain, Subdomain, DNS, HTTP, Telnet, FTP, Address Resolution                        |
| TCP/IP        | Features, Segment, Handshake, Flow/Error/Congestion Control, IP Datagram, IPv4, IPv6 |
| IP Addressing | Classful/Classless, Subnetting, NAT, Masquerading, IP Tables                         |
| Routing       | Intra/Inter-domain, Unicast, Multicast, Broadcast                                    |
| Email         | POP3, SMTP (+ IMAP, MIME, security add-ons)                                          |

---
