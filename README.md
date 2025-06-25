# Local-Network-Port-Scan

Task 1: Scan Your Local Network for Open Ports

Objective: Learn to discover open ports on devices in your local network to understand network exposure.

Tools Used:

    Kali Linux
  
    Nmap 7.95

Local Network Details:

    Local IP: 10.0.2.15
  
    Subnet: 10.0.2.0/24

Procedure:

    1. Installed the nmap (already installed in the system), in the screenshot named nmap-install.png
    
    2. Found the ip address of the network using "ipconfig"
    
    3. Done the port scan on the network using nmap and saved the network scan data in "scan-result.txt" also attached a screenshot of it.
    
Risk Analysis:

    Port 135 (msrpc) – Commonly exploited on Windows machines.
  
    Port 445 (microsoft-ds) – SMB; vulnerable to WannaCry, EternalBlue.
  
    Port 3306 (MySQL) – Open MySQL without authentication is a serious risk.

Risks:

    Unauthorized access
  
    Exploitation via known vulnerabilities
  
    Data breaches
