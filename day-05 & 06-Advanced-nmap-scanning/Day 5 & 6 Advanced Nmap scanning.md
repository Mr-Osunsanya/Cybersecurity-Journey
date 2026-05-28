# Day 5 & 6

#  Advanced Nmap Scanning & Enumeration (Ubuntu)

##  Overview
This lab focuses on advanced network reconnaissance using Nmap on Ubuntu Linux.  
It goes beyond basic scanning to explore how systems expose services, ports, and operating system details.

The goal is to understand how cybersecurity professionals identify vulnerabilities and map network environments.

---

## Objectives
- Perform advanced Nmap scans
- Identify open ports and services
- Detect service versions
- Perform OS fingerprinting
- Understand SYN and UDP scanning
- Learn basic network enumeration techniques

---

##  Tools Used
- Nmap
- Ubuntu Terminal (Bash)
- Localhost (safe testing environment)

---


## Obeservations and Understanding

1. NMAP SCANNING
Runnig the command to scan for ports. I understood that localhost Nmap scan is a basic way to check what services are running on your own computer. When you run nmap localhost, it shows the open ports and tells you which services are currently active. This helps you understand what your system is exposing and what could potentially communicate over the network.

2. SERVICE VERSION DETECTION
When I ran nmap -sV localhost, it goes a step further by identifying the specific service and its version running on each open port. For example, it can tell you not just that SSH is running, but the exact software version of SSH.

3. OPERATION SERVICE DETECTION
Service version detection in Nmap (nmap -sV) is used to identify what specific services are running on open ports and the exact software versions behind them. Instead of just showing that a port is open, it gives more detail like whether it is SSH, HTTP, or another service, and the version of that software. This is important because different versions can have different vulnerabilities.
This is when the "fingerprints" plays out. OS fingerprinting is how tools like Nmap try to identify the operating system of a device by studying how it responds to network requests.

Instead of directly asking “what OS are you?”, this tool sends small packets and observes the unique patterns in the replies. Every operating system (Windows, Linux, macOS, etc.) handles networking slightly differently, even if the difference is very small.

These differences are called “fingerprints”.

4. ENUMERATION SCANNING
This is what it's usually know as an aggressive scan. An aggressive scan (nmap -A) goes even further. It combines multiple scan types in one command, including service version detection, operating system detection, and additional information gathering like traceroute. It gives a more complete picture of the target system in a single scan.