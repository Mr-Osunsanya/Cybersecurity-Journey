#  Wireshark Packet Analysis Lab

---

##  Introduction

This lab focuses on understanding how computers communicate over a network by capturing and analyzing real traffic using Wireshark.

Wireshark is a network protocol analyzer that allows us to see data packets as they travel between devices. Instead of guessing how networking works, we directly observe:
- DNS requests
- ICMP messages (ping)
- TCP connections
- UDP communication

This helps bridge the gap between theory (OSI/TCP-IP models) and real-world network behavior.

---

##  Objectives

By completing this lab, the following goals are achieved:

- Understand how DNS, ICMP, TCP, and UDP work in real networks  
- Capture live traffic using Wireshark on Ubuntu  
- Map network activity to TCP/IP model layers  
- Interpret packet structures step by step  
- Connect terminal commands to actual network packets  
- Develop foundational skills used in cybersecurity analysis and SOC monitoring  

---

## Tools Used
 
- Ubuntu Terminal (Bash shell)  
- Web browser (Firefox/Chrome)  
- Network utilities:
  - `ping`
  - `nslookup`

---

#  LAB SETUP PROCESS

Before capturing traffic, Wireshark must be started correctly:

1. Open Wireshark
2. Select active network interface:
   - `wlan0` (Wi-Fi) OR `eth0` (Ethernet)
3. Click **Start Capture**

At this point, Wireshark begins recording all network packets passing through the system.

---

