# Virtual Network Lab

Virtual SOC Lab for Network Security and Analysis. 

## Objective

This project aims to build a secure, virtualized network environment demonstrating essential network architecture, cybersecurity, and access control skills. Simulating a real-world network setup showcases proficiency in deploying firewall rules, managing user access through Identity and Access Management (IAM), and implementing network hardening techniques to protect against potential threats.

This project aims to illustrate practical experience in creating and managing a secure, adaptable network that meets the security and accessibility needs expected in a professional IT environment.

### Key Features

- <b>Network Security and Monitoring:</b> Configure incoming and outgoing firewall rules, set up continuous traffic monitoring, and implement intrusion detection to ensure robust protection of network assets.
  
- <b>Active Directory Integration:</b> Set up Identity and Access Management (IAM) through Active Directory, including user and group management, strong password policies, and permissions for secure resource access.
  
- <b>File Sharing and Public Resources:</b> Enable file-sharing capabilities (e.g., SMB or NAS) and securely host public-facing resources in a DMZ, balancing accessibility and security as guided by the CIA Triad (Confidentiality, Integrity, Availability).
  
- <b>Platform Flexibility:</b> Lab creation will emulate real-world Cisco Packet Tracer solutions.

### Skills Learned

- Planning and deploying a network architecture 
- Traffic monitoring 
- Establishing firewall rules 
- Setting up and managing IAM (Identity and Access Management), including users and groups in Active Directory 
- Network hardening techniques

### Tools Used

- Active Directory
- Cisco Packet Tracer for network simulation
- Wireshark for traffic analysis
- pfSense as a firewall
- Snort for intrusion detection
- PowerShell for scripting and automation

## Steps

SOC-Analyst-Virtual-Lab/
│
├── README.md
├── LabSetup/
│   ├── AD_Setup_Instructions.md
│   ├── pfSense_Configuration_Guide.md
│   ├── Snort_Setup_Guide.md
│   └── Cisco_Packet_Tracer_Topology.pkt
│
├── Captures/
│   ├── Normal_Traffic.pcap
│   ├── Port_Scan_Traffic.pcap
│   └── Brute_Force_Attempt.pcap
│
├── Reports/
│   ├── Traffic_Analysis_Report.md
│   ├── Firewall_Rule_Config.md
│   └── Intrusion_Alert_Report.md
│
└── Scripts/
    ├── PowerShell_Security_Audit.ps1
    ├── Custom_Wireshark_Filters.txt
    └── Snort_Rules_Config.txt

