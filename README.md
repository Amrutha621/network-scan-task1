# Task 1: Network Scan using Nmap

This repository contains the output for **Task 1** of the Cybersecurity Internship at **Elevate Labs**.

## 🔍 Objective
Scan the local network to discover open ports and understand network exposure.

## 🛠 Tools Used
- [Nmap](https://nmap.org/) – for port scanning
- Windows Command Prompt
- (Optional) [Wireshark](https://www.wireshark.org/) – for packet analysis

## 🧠 Steps Performed
1. Installed Nmap on Windows.
2. Found my local IP range using `ipconfig` – identified range as `192.168.0.0/24`.
3. Ran a TCP SYN scan:
   ```bash
   nmap -sS 192.168.0.0/24

Saved results to scan_results.txt using:
bash
Copy code
nmap -sS 192.168.0.0/24 -oN scan_results.txt

 Output
See the scan_results.txt file in this repository.

🔐 Observations
Identified active devices on the network.

Noted the open ports and services on each.

Open ports such as 22 (SSH), 80 (HTTP), and 443 (HTTPS) can be entry points if not secured.

📚 Key Concepts Learned
What open ports are and how they can expose a network

Basics of TCP SYN scanning

Importance of securing unused or unnecessary ports


