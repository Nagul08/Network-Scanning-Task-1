# Network-Scanning-Task-1
# 🔥 Nmap Recon Mission — Task 1  
Cyber Security Internship · Network Mapping & Exposure Analysis

## 🛰️ Overview
This task focused on performing a detailed **network reconnaissance scan** using **Nmap** to identify live hosts, open ports, and running services within a local `/24` subnet.  
The goal: understand how attackers gather intel and how defenders can secure their environment.

---

## 🔎 What Was Done
- Performed a **TCP SYN Scan** across the local network  
- Detected active devices and enumerated their open ports  
- Identified exposed services running on discovered hosts  
- Analyzed results to understand potential attack surfaces  
- Verified findings with **Wireshark** packet observations

---

## ⚙️ Tools & Techniques Used
- **Nmap**  
  - SYN Scan (`-sS`)  
  - Subnet scan (`192.168.x.0/24`)  
  - Service detection where needed (`-sV`)  
- **Wireshark**  
  - Packet tracing for scan traffic  
- Basic network analysis principles

---

## 📁 Included Files
- `scan_results.txt`  
  Full raw Nmap output containing host discovery, port states, and service information.

- **Screenshots Folder**  
  Terminal screenshots captured during scan execution.

- `README.md`  
  Steps, observations, and security notes compiled from the task.

---

## 🧠 Key Skills Practiced
- Network Reconnaissance  
- Port Scanning & Enumeration  
- Interpreting Nmap Output  
- Identifying Exposure Points  
- Intro-level Defensive Analysis  
- Packet Verification via Wireshark

---

## ⚡ Insight
> “Every open port reveals more about a system than you think. Recon is where the real story begins.”

---

## 📌 Notes
This task was completed as part of the cybersecurity internship to build foundational skills in understanding how networks are mapped, evaluated, and secured.
