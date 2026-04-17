#  OSI Model & Security Analysis (With Real-Life Examples)

>  “To defend a network, you must understand it layer by layer.”

---

##  Prepared by:
Abdu  
Cybersecurity Trainee   

---

#  Introduction

The OSI (Open Systems Interconnection) Model is a conceptual framework that explains how data travels from one device to another through 7 layers.

Each layer:
- Has a specific function  
- Uses real-world technologies  
- Faces unique security threats  
- Requires specific protection mechanisms  

---

#  OSI Layers Overview

| Layer | Name |
|------|------|
| 7 | Application |
| 6 | Presentation |
| 5 | Session |
| 4 | Transport |
| 3 | Network |
| 2 | Data Link |
| 1 | Physical |

---

#  7. Application Layer

##  Function
Provides services directly to the user

##  Examples
- Web browsers (Chrome, Firefox)  
- Email (Gmail, Outlook)  
- FTP applications  

##  Attacks
- Phishing  
- SQL Injection  
- Cross-Site Scripting (XSS)  

##  Prevention
- Input validation  
- Use HTTPS  
- User awareness  

---

#  6. Presentation Layer

##  Function
Handles:
- Encryption  
- Data formatting  
- Compression  

##  Examples
- SSL/TLS (HTTPS)  
- JPEG / PNG images  
- UTF-8 encoding  

##  Attacks
- SSL/TLS attacks  
- Man-in-the-Middle (MITM)  

##  Prevention
- Strong encryption  
- Valid certificates  

---

#  5. Session Layer

##  Function
Manages sessions between devices

##  Examples
- Logging into websites  
- Zoom / Google Meet calls  
- Online gaming  

##  Attacks
- Session hijacking  
- Replay attacks  

##  Prevention
- Session timeout  
- Secure authentication  
- Token protection  

---

#  4. Transport Layer

##  Function
Ensures data delivery using protocols

##  Examples
- TCP → Reliable communication  
- UDP → Fast communication  
- Ports (80, 443, etc.)  

##  Attacks
- SYN Flood (DoS attack)  
- Port scanning  

##  Prevention
- Firewalls  
- Intrusion Detection Systems (IDS)  
- Rate limiting  

---

#  3. Network Layer

##  Function
Handles:
- Routing  
- IP addressing  

##  Examples
- IP addresses (192.168.1.1)  
- Routers  
- Packet forwarding  

##  Attacks
- IP spoofing  
- ICMP flood  

##  Prevention
- VPN  
- Packet filtering  
- Routing security  

---

#  2. Data Link Layer

##  Function
Handles communication in local network using MAC addresses

##  Examples
- MAC addresses  
- Ethernet  
- Switches  

##  Attacks
- ARP spoofing  
- MAC flooding  

##  Prevention
- Port security  
- Dynamic ARP inspection  
- Switch configuration  

---

#  1. Physical Layer

##  Function
Transmits raw data through physical media

##  Examples
- Ethernet cables  
- Network cards (NIC)  
- Wi-Fi signals  

##  Attacks
- Cable tapping  
- Hardware theft  
- Signal interference  

##  Prevention
- Physical security  
- Restricted access  
- Surveillance systems  

---

#  Real-Life Example (Telegram Communication)

When you send a message on Telegram:

1. Application Layer → You type message  
2. Presentation Layer → Message encrypted  
3. Session Layer → Session maintained  
4. Transport Layer → TCP/UDP sends data  
5. Network Layer → Routed via IP  
6. Data Link Layer → MAC delivery  
7. Physical Layer → Sent via Wi-Fi  

---

#  Key Security Insight

👉 Attacks can happen at ANY layer  
👉 Security must be applied at ALL layers  

---

#  Conclusion

The OSI model is not just theory — it is the foundation of cybersecurity.

✔ Each layer has a role  
✔ Each layer has vulnerabilities  
✔ Each layer needs protection  

---

#  Final Thought

> “A secure system is built by protecting every layer — not just one.”
