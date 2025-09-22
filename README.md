# Cybersecurity_Internship_Task_1
Task 1: Scan Local Network for Open Ports

## Objecvtive
Performing network reconnaissance on my local network to discover open ports and understand service exposure. Save scan outputs, analyze findings, and recommend remediations.

## Tools Used
- **Nmap** (Network Mapper)
- **Wireshark** (Network Traffic Analyzer)
- **Kali Linux** (Operating System)

## Steps:
- Find your local IP range (e.g., 192.168.1.0/24).
- Run: nmap -sS 192.168.1.0/24 to perform TCP SYN scan.
- Note down IP addresses and open ports found.
- Optionaly analyze packet capture with Wireshark.
- Research common services running on those ports.
- Save scan results as a text or HTML file.

## Conclusion:
This exercise demonstrated how port scanning exposes the attack surface of a local network. Using Nmap for discovery and Wireshark for packet verification allowed identification of open services and potential weaknesses. The recommendations above will reduce exposure and improve network security.
