OSI Model and Security Analysis (With Real-Life Examples)

Prepared by: Abdu

Introduction

The OSI (Open Systems Interconnection) model explains how data is transmitted across a network using seven layers. Each layer has specific functions, real-world applications, possible attacks, and protection mechanisms.


📚 OSI Layers Overview

Layer Name

7 Application
6 Presentation
5 Session
4 Transport
3 Network
2 Data Link
1 Physical


 7. Application Layer

Function:

Provides services directly to users.

Examples:

Web browsers (Chrome, Firefox)

Email services (Gmail, Outlook)

File transfer (FTP applications)


Attacks:

Phishing

SQL Injection

Cross-Site Scripting (XSS)


Prevention:

Input validation

Use HTTPS

User awareness



 6. Presentation Layer

Function:

Handles data encryption, formatting, and compression.

Examples:

SSL/TLS encryption (HTTPS websites)

Image formats (JPEG, PNG)

Data encoding (ASCII, UTF-8)


Attacks:

SSL/TLS attacks

Man-in-the-middle (MITM)


Prevention:

Strong encryption

Secure certificates




 5. Session Layer

Function:

Manages communication sessions between devices.

Examples:

Logging into a website

Video calls (Zoom, Google Meet)

Online gaming sessions


Attacks:

Session hijacking

Replay attacks


Prevention:

Session timeout

Secure authentication



 4. Transport Layer

Function:

Ensures reliable data transmission using protocols.

Examples:

TCP (reliable data transfer)

UDP (fast streaming)

Port numbers (e.g., port 80, 443)


Attacks:

SYN flood (DoS)

Port scanning


Prevention:

Firewalls

Intrusion Detection Systems (IDS)



 3. Network Layer

Function:

Handles routing and logical addressing (IP).

Examples:

IP addresses (192.168.1.1)

Routers

Packet forwarding


Attacks:

IP spoofing

ICMP flood


Prevention:

VPN

Packet filtering



 2. Data Link Layer

Function:

Handles communication within the same network using MAC addresses.

Examples:

MAC addresses

Ethernet

Switches


Attacks:

ARP spoofing

MAC flooding


Prevention:

Switch security

ARP inspection



 1. Physical Layer

Function:

Transmits raw data through physical media.

Examples:

Ethernet cables

Network interface cards (NIC)

Wi-Fi signals


Attacks:

Cable tapping

Hardware theft

Signal interference


Prevention:

Physical security

Restricted access


Conclusion

Each OSI layer plays a vital role in communication and has real-world applications. However, each layer is also vulnerable to specific attacks. Therefore, applying security measures at every layer is essential to protect the entire system.
