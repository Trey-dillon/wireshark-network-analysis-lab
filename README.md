# 🦈 Wireshark Network Analysis Lab

![Wireshark](https://img.shields.io/badge/Wireshark-Network%20Analysis-1679A7?style=for-the-badge&logo=wireshark)
![Networking](https://img.shields.io/badge/Focus-TCP%2FIP%20Analysis-blue?style=for-the-badge)

---

# 📌 Overview

This project documents my hands-on practice analyzing network traffic using Wireshark.

The purpose of this lab is to develop skills used in Security Operations Center (SOC) environments, including packet analysis, protocol investigation, and identifying suspicious network activity.

---

# Lab Environment

## Tools Used

- Wireshark
- VirtualBox
- Windows/Linux Virtual Machines

---

# Analysis Skills Practiced

## Packet Capture Analysis

Investigated:

- Network conversations
- Source and destination addresses
- Communication patterns
- Protocol behavior

---

## Protocol Analysis

Analyzed:

- TCP
- UDP
- DNS
- HTTP
- ICMP
- ARP

---

## Network Troubleshooting

Used Wireshark to identify:

- Connectivity issues
- Failed connections
- Packet retransmissions
- Network behavior

---

# Lab Exercises

## DNS Investigation

Reviewed DNS queries and responses to understand:

- Domain lookups
- DNS request flow
- Client/server communication


## TCP Analysis

Analyzed:

- Three-way handshake
- TCP flags
- Connection states
- Retransmissions


## ICMP Troubleshooting

Investigated:

- Ping requests
- Echo replies
- Connectivity testing

---

# Security Concepts

Skills demonstrated:

- Network visibility
- Traffic monitoring
- Packet inspection
- Protocol understanding
- Basic threat analysis

---

# Screenshots

## 1. Filtering Out Unwanted Packets

![Filtering Out Unwanted Packets](screenshots/Wireshark%20screenshot%201%20Filtering%20out%20unwanted%20packets.png)

Applied Wireshark display filters to isolate relevant network traffic and remove unrelated packets.

---

## 2. Following an HTTP Stream

![Follow HTTP Packet](screenshots/Wireshark%20screenshot%202%20follow%20HTTP%20Packet.png)

Used **Follow HTTP Stream** to inspect the conversation between a client and server.

---

## 3. Exploring Port 80 Traffic

![Port 80 Analysis](screenshots/Wireshark%20screenshot%203%20Exploring%20port%2080%20encryption.png)

Examined HTTP traffic over TCP port 80 to understand request and response behavior.

---

## 4. Exploring Coloring Rules and TCP Flags

![Coloring Rules](screenshots/Wireshark%204%20exploring%20coloring%20rules%20and%20flags.png)

Explored Wireshark's coloring rules and TCP flags to quickly identify different packet types.

---

## 5. ICMP Google Ping

![ICMP Ping](screenshots/Wireshark%205%20ICMP%20google%20ping.png)

Captured ICMP Echo Requests and Echo Replies while testing connectivity using `ping`.

---

# Future Improvements

- Analyze malware traffic samples
- Add PCAP investigation reports
- Practice SOC alert investigations
- Integrate with SIEM tools
