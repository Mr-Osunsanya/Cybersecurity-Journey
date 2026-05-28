#  Day 9 & 10 — Linux Processes & System Monitoring

##  Overview
Today’s lab focused on understanding how Linux runs and manages processes in real time. I explored how to monitor active programs, inspect system resource usage, identify running services, and understand how Linux keeps track of processes using Process IDs (PIDs).

This session helped me connect Linux system activity to cybersecurity monitoring and understand how analysts inspect systems for suspicious behavior.

---

# What I Practiced

- Viewing running processes
- Understanding process information using `ps aux`
- Monitoring CPU and memory usage
- Viewing active services
- Understanding Process IDs (PID)
- Learning how Linux manages background activity
- Inspecting network-related services and connections

---

# Understanding Linux Processes

A process is any program currently running on the system. This task help me understood that linux constantly runs multiple processes in the background to manage applications, services, networking, and system operations.

Using process monitoring commands helped me understand:
- which programs are active
- which user owns a process
- how much CPU or memory is being used
- what commands are running in the system

---

# Process Monitoring with `ps aux`

The `ps aux` command displayed all active processes running on the system.

It provided detailed information such as:
- the user running the process
- Process ID (PID)
- CPU usage
- memory usage
- process state
- the actual command being executed

This helped me understand how Linux tracks and manages running programs internally.

---

# Important Process Information Learned

| Section | Meaning |
|---|---|
| `USER` | The user running the process |
| `PID` | Unique identifier for each process |
| `%CPU` | CPU usage by the process |
| `%MEM` | RAM usage by the process |
| `STAT` | Current process state |
| `COMMAND` | Program or command running |

This showed me how Linux keeps detailed records of system activity.

---

# Real-Time Monitoring

I used monitoring tools to observe system activity in real time, including:
- CPU usage
- memory usage
- active processes
- system load

This helped me understand how Linux behaves while applications and services are running.

---

# Services & Background Activity

I also explored how Linux runs background services and system processes automatically.

This helped me understand:
- how services stay active in the background
- how Linux handles system operations
- how important services support networking and applications

---

# Network & Process Connection

Part of the lab involved inspecting network-related services and active connections. This showed how processes can interact with the network and how services open ports for communication.

This helped connect Linux process monitoring with earlier networking and Nmap labs.

---

# Cybersecurity Relevance

This lab showed why process monitoring is important in cybersecurity due to my reasearchs and past studies.

Security analysts often inspect processes to:
- identify suspicious activity
- detect malware or hidden programs
- monitor unusual CPU or memory usage
- investigate compromised systems

Understanding processes is important because many attacks rely on malicious programs running silently in the background.

---

# Skills Improved

Through this lab, I improved my understanding of:
- Linux process management
- system monitoring
- resource usage analysis
- background services
- process identification (PID)
- basic security monitoring concepts

---

# Reflection

This session helped me better understand how Linux systems operate internally and how running processes connect to overall system activity. It also showed how monitoring tools can be used to observe applications, services, and resource usage in real time.

The lab made Linux system monitoring feel more practical and connected it directly to cybersecurity and system analysis.