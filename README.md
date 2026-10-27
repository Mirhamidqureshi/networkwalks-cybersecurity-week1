# 🚀 Networkwalks Cybersecurity Program — Week 1

**Author:** Hamid Ali  
**Program:** Networkwalks Cybersecurity Program  
**Batch:** B084  
**Project:** Cybersecurity & Pentesting Lab Setup

## 📌 Project Overview

This repository documents my Week 1 hands-on learning experience in the Networkwalks Cybersecurity Program. I built a virtual cybersecurity lab and practised networking fundamentals and network traffic analysis using Wireshark.

## 🛠️ Tools Used

- VirtualBox — Virtual machine management
- Kali Linux — Cybersecurity practice environment
- Wireshark — Network packet and protocol analysis

## ✅ Tasks Completed

- Installed and configured VirtualBox.
- Imported and configured Kali Linux.
- Created a private NAT Network.
- Configured and verified network settings.
- Explored NAT vs. NAT Network.
- Practised network traffic analysis using Wireshark.

## 🔎 Wireshark Practice

Wireshark was the highlight of my learning journey. I practised identifying and analysing:

- DNS queries and responses
- TCP three-way handshakes and SYN flags
- HTTP requests and responses
- ICMP echo requests and replies
- Source and destination IP addresses
- TCP streams and retransmissions
- Protocol statistics and display filters

### Useful Display Filters

**DNS traffic**
```wireshark
dns
```

**ICMP traffic**
```wireshark
icmp
```

**Traffic to or from a host**
```wireshark
ip.addr == 192.168.1.20
```

**Initial TCP SYN packets**
```wireshark
tcp.flags.syn == 1 && tcp.flags.ack == 0
```

**TCP retransmissions**
```wireshark
tcp.analysis.retransmission
```

## 🛡️ Hands-on SOC Labs

I completed practical SOC exercises involving:

- Identifying suspicious source IP addresses
- Following TCP streams to inspect conversations
- Analysing HTTP traffic and clear-text credentials in lab captures
- Investigating repeated login attempts
- Understanding packet-level evidence and network behaviour

These exercises helped me develop an investigative mindset and understand how network traffic analysis supports security monitoring and incident investigation.

## 🏆 Learning Achievements

- Completed the Week 1 cybersecurity lab setup.
- Scored 90% in the basic Wireshark quiz.
- Scored 100% in the advanced Wireshark quiz.
- Scored 100% in the HTTP Plain Text Credentials SOC lab.

## 📸 Screenshots

Screenshots of my Kali Linux setup, Wireshark analysis, and completed SOC labs will be added to this repository.

## 🎯 Key Takeaways

This project strengthened my understanding of virtual networking, common protocols, packet inspection, and security investigation fundamentals. It also increased my interest in Network Security and SOC analysis.

## 🙏 Acknowledgment

A huge thank you to **Waqas Karim (CCIE)** and the Networkwalks team for their guidance and practical learning resources.

## ⚖️ Responsible Use

All exercises are intended for authorised lab environments. Never publish sensitive credentials, session tokens, or private network captures.

---

*Learning by doing. Improving one lab at a time. 🔐*
