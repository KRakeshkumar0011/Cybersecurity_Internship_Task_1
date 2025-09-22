# Cybersecurity_Internship_Task_1
Task 1: Scan Local Network for Open Ports

## Objecvtive
Performing network reconnaissance on my local network to discover open ports and understand service exposure. Save scan outputs, analyze findings, and recommend remediations.

## Tools Used
- **Nmap** (Network Mapper)
- **Wireshark** (Network Traffic Analyzer)
- **Kali Linux** (Operating System)

# Commands Used:
- Check Nmap Version:
<br>nmap --version
- Check IP Address:
<br>ifconfig
- Perform TCP SYN Scan:
<br>nmap -sS 192.168.1.0/24
- Store Scan Output in a Text File:
<br>nmap -sS 192.168.1.0/24 > scan_Result.txt
- Packet Capture in Wireshark
<li>Captured network traffic while running Nmap scan.</li>
<li>Saved as: wiresharkscan.pcapng</li>
