# 🦈 Wireshark – Network Traffic Analysis and Packet Sniffing

## 📌 Project Overview

This project demonstrates the practical use of **Wireshark** for capturing, filtering, and analyzing network packets.

The project was performed in a controlled laboratory environment using Kali Linux and a test network. Different network protocols and packet exchanges were captured and analyzed to understand network communication and identify potential security concerns.

---

## 🎯 Objectives

* Understand Wireshark and packet capture fundamentals.
* Capture live network traffic in a controlled environment.
* Analyze ICMP, ARP, TCP, and HTTP traffic.
* Understand packet headers and protocol communication.
* Identify source and destination information.
* Analyze HTTP requests and responses.
* Examine potential security risks associated with plaintext network traffic.
* Document packet analysis findings.

---

## 🛠️ Tools & Technologies

* **Wireshark**
* **Kali Linux**
* **Metasploitable 2**
* **Oracle VirtualBox**
* **TCP/IP**
* **ICMP**
* **ARP**
* **TCP**
* **HTTP**

---

## 🧪 Test Environment

```text
Kali Linux
    │
    │ Wireshark
    ▼
Controlled Lab Network
    │
    ▼
Metasploitable 2
```

The packet captures and analysis were performed within a controlled laboratory environment.

---

## 🔎 Packet Analysis Performed

### 1. ICMP Traffic Analysis

ICMP packets were captured and analyzed to understand network reachability and request/response communication.

Key observations included:

* ICMP Echo Request
* ICMP Echo Reply
* Source and destination addresses
* Packet sequence and timing

---

### 2. ARP Traffic Analysis

ARP packets were analyzed to understand IP-to-MAC address resolution within the local network.

Key observations included:

* ARP Request
* ARP Reply
* Sender and target IP addresses
* Sender and target MAC addresses

---

### 3. TCP Traffic Analysis

TCP packets were captured to study connection establishment and packet communication.

The analysis included:

* Source and destination ports
* TCP flags
* Sequence numbers
* Acknowledgment numbers
* TCP connection behavior

---

### 4. HTTP Traffic Analysis

HTTP traffic was captured and analyzed to understand communication between a client and web server.

The analysis included:

* HTTP requests
* HTTP responses
* Request URI
* HTTP methods
* Status codes
* Host information
* Packet details

---

### 5. Plaintext HTTP Credential Analysis

The project also demonstrated the security risk associated with transmitting sensitive information over unencrypted HTTP.

The captured traffic was analyzed to understand how plaintext information can potentially be exposed when encryption is not used.

---

## 🔬 Wireshark Filters Used

Examples of protocol filters used during analysis:

```text
icmp
arp
tcp
http
```

Additional filters were applied where required to isolate specific packets and communication flows.

---

## 📊 Key Findings

The packet analysis demonstrated:

* How different network protocols communicate.
* How packet headers provide useful network information.
* How ARP resolves local network addresses.
* How TCP establishes and maintains connections.
* How HTTP requests and responses can be inspected.
* The security risks associated with plaintext HTTP communication.

---

## 📸 Project Screenshots

Screenshots of packet captures and analysis are available in:

**`Screenshots/`**

These include ICMP, ARP, TCP, HTTP, and other relevant packet-analysis demonstrations.

---

## 📄 Project Documentation

**Final Report:**
`Wireshark_Project_Final_Report.pdf`

**Presentation:**
`Wireshark_Project_Presentation.pptx`

---

## 🎓 Key Learning Outcomes

This project provided practical experience in:

* Packet capture
* Network protocol analysis
* TCP/IP fundamentals
* Packet filtering
* ICMP and ARP analysis
* TCP communication analysis
* HTTP traffic inspection
* Network security analysis
* Identifying risks in plaintext communication

---

## ⚠️ Disclaimer

All packet capture and network analysis activities were performed in a **controlled and authorized laboratory environment for educational purposes**.

The techniques demonstrated should only be used on networks and systems for which proper authorization has been obtained.

---

## 👨‍💻 Author

**Manohar Chowdary**

Cybersecurity | Network Security | SOC Operations

