# Cybersecurity_Internship_Task_1
Task 1: Scan Local Network for Open Ports

## Objecvtive
Performing network reconnaissance on my local network to discover open ports and understand service exposure. Save scan outputs, analyze findings, and recommend remediations.

## Tools Used
- **Nmap** (Network Mapper)
- **Wireshark** (Network Traffic Analyzer)
- **Kali Linux** (Operating System)

<h4>Commands Used:</h4>
<ul>
  <li>Check Nmap Version:<br>nmap --version</li>
  <li>Check IP Address<br>ifconfig</li>
  <li>Perform TCP SYN Scan<br>nmap -sS 192.168.1.0/24</li>
  <li>Store Scan Output in a Text File<br>nmap -sS 192.168.1.0/24 > scan_Result.txt</li>
  <li>Packet Capture in Wireshark<br>
    <ul type='circle'>
      <li>Captured network traffic while running Nmap scan.</li>
      <li>Saved as: wiresharkscan.pcapng</li>
    </ul>
  </li>
</ul>
