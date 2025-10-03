# Task 5 – Wireshark Network Traffic Analysis  

## 📌 Project Overview  
This repository contains the deliverables for **Task 5: Capture and Analyze Network Traffic Using Wireshark**.  
The objective was to capture live network packets, apply filters, and identify commonly used protocols.  
The project also demonstrates anonymization of captured traffic to protect personal IP addresses.  

---

## 🛠 Tools Used  
- **Wireshark** (Free and open-source network protocol analyzer)  
- Windows 10 (Host environment for capturing traffic)  

---

## 📋 Steps Followed  
1. Installed Wireshark.  
2. Started packet capture on the active network interface.  
3. Generated traffic by browsing websites and pinging servers.  
4. Stopped the capture after ~1 minute.  
5. Applied filters for different protocols (HTTP, TCP, TLS, ICMP).  
6. Saved the capture as `.pcap`.  
7. **Anonymized the file to hide sensitive IP details**.  
8. Documented findings in a short report.  

---

## 📂 Deliverables  
- **Report (Word/PDF)** – Contains objective, methodology, screenshots, protocols identified, observations, and conclusion.  
- **Screenshots** – Filtered views of HTTP, TCP, TLS, and ICMP traffic in Wireshark.  
- **Anonymized `.pcap` file** – The sanitized capture file with hidden IP addresses.  

---

## 🔍 Protocols Identified  
- **HTTP** – Web communication traffic.  
- **TCP** – Transport protocol ensuring reliable delivery.  
- **TLS** – Encrypted HTTPS communication.  
- **ICMP** – Diagnostic and connectivity testing (ping).  

---

## 🔒 Anonymization Process  
To protect personal data, the `.pcap` file was anonymized before sharing.  
- IP addresses and host details were masked to prevent exposure of private network information.  
- Only protocol-level details (HTTP, TCP, TLS, ICMP) remain visible for analysis.  
- This ensures the file is safe to upload publicly while still useful for protocol study.  

---

## ✅ Outcome  
This task improved practical skills in **packet capture, filtering, and protocol analysis**.  
It also highlighted the importance of **data anonymization** when sharing `.pcap` files publicly.  

---
