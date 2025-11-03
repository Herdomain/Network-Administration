# NETWORK ADMINISTRATION

## Executive Summary

This project focuses on improving visibility into network assets within a simulated lab environment. Using Nmap and Wireshark on a Kali virtual machine, I performed scans to identify devices, services, and communication patterns. The lab included a Windows Server and a Linux Server, and all data collected through scanning was verified directly on the devices.

The results were compiled into a structured report that includes an asset inventory, key findings from the network traffic analysis, and a basic network topology with recommendations. This project highlights the importance of accurate documentation and asset identification as part of risk awareness and supports foundational practices aligned with audit readiness and system monitoring.

## Objective

The primary goal of this project was to identify, verify, and document all devices operating within a virtual lab network.
Using Nmap for active scanning and Wireshark for traffic capture, I collected detailed information on each device’s configuration, services, and communication activity. Each data point was validated through direct examination and cross-referenced between tools to ensure accuracy. 

The final deliverable was a structured report presenting this information in a format suitable for internal auditing, policy development, and compliance documentation.

### Skills Learned

- Proficiency in identifying and analyzing processes and services across Windows and Linux systems.
- Configured and managed virtual machines to replicate segmented network environments for realistic risk assessment scenarios.
- Captured and interpreted network traffic to understand communication patterns, detect anomalies, and trace service activity using Wireshark.
- Applied knowledge of IPv4 architecture and subnetting to propose efficient and secure network segmentation.

### Virtual Machine Setup
- Windows Server
- Linux Server
- Kali Server (Primary platform used for this analysis)
  
### Tools Used

- Nmap: For active scanning and device enumeration
- Wireshark: For passive packet capture and protocol analysis
- VirtualBox: For lab environment deployment and simulation scenarios.


## Steps

<img width="313" height="100" alt="image" src="https://github.com/user-attachments/assets/357772ac-688d-4eb9-b6b3-351034dfdd2d" />

Fig .1.1 Nmap scan results showing that the device at IP address 10.0.2.1 is active and running a DNS service. This confirms the presence of a networked system and helps identify what services are exposed.

Recommended Screenshots *delete later*
- Nmap scan output identifying devices and open ports
- Wireshark packet capture filtered by IP
- OS and service verification on each machine
- Network topology diagram with IP ranges

