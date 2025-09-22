# Cybersecurity_Internship_Task_1
Task 1: Scan Local Network for Open Ports

## Objecvtive
Perform network reconnaissance on my local network to discover open ports and understand service exposure. Save scan outputs, analyze findings, and recommend remediations.

## Tools Used
- **Nmap** (Network Mapper)
- **Wireshark** (Network Traffic Analyzer)
- **TCPdump** (Network Traffic Analyzer)
- **Kali Linux** (Operating System)

  ## Steps I followed
1. Identified local network CIDR: `192.168.1.0/24`
2. Quick scan to find live hosts & top ports:
   - `sudo nmap -sS -F 192.168.1.0/24 -oN scans/quick_scan.txt`
3. Targeted scans for interesting hosts:
   - `sudo nmap -sS -sV -A -p- 192.168.1.101 -oA scans/host1_full`
4. Packet capture during scan:
   - `sudo tcpdump -i <interface> -w scans/scan_capture.pcap`
5. Analyzed PCAP in Wireshark (filters used: `tcp.flags.syn == 1 && tcp.flags.ack == 0`)
