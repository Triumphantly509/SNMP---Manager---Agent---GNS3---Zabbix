# SNMP---Manager---Agent---GNS3---Zabbix


# GNS3 & Zabbix – SNMP Network Monitoring Lab

## Project Overview

Build a network monitoring environment using **GNS3, Cisco IOS, SNMPv2c, and Zabbix**. The project demonstrates how to monitor a virtual Cisco router, collect network performance metrics, and visualize device availability through a centralized Zabbix dashboard.

## Technologies & Tools

| Component | Technology / Version |
|---|---|
| Operating System | Ubuntu 24.04.1 LTS |
| Network Simulation | GNS3 2.2.61 |
| Monitoring Platform | Zabbix Server 7.0.32 |
| Database | MySQL 8.0 |
| Web Server | Apache |
| PHP | 8.3 |
| Network Device | Cisco 7200 Router |
| Cisco IOS | 15.3(3)XB12 |
| Monitoring Protocol | SNMPv2c |

## Network Topology & IP Addressing

| Device | Interface | IP Address |
|---|---|---|
| Ubuntu Monitoring Server | gns3tap | `192.168.10.1/24` |
| Cisco 7200 Router | FastEthernet0/0 | `192.168.10.2/24` |

**Connectivity:** GNS3 Cloud/TAP interface connecting the virtual Cisco router to the Ubuntu monitoring server.

## Project Objectives

### 1. SNMP Configuration – Cisco IOS

- Configure SNMPv2c with a read-only community.
- Configure SNMP system location and contact information.
- Enable SNMP communication over UDP port 161.
- Verify SNMP connectivity using Linux SNMP utilities.

### 2. Zabbix Server Deployment – Ubuntu

- Install and configure Zabbix Server 7.0.32.
- Configure MySQL as the database backend.
- Integrate Apache and PHP for the Zabbix web interface.
- Establish communication between Zabbix and the GNS3 virtual network.

### 3. Network Monitoring & Visualization

Use SNMP polling and Zabbix monitoring to collect and visualize:

- Router availability and ICMP connectivity.
- Network interface operational status.
- Incoming and outgoing interface traffic.
- Device uptime.
- CPU and memory utilization.
- SNMP system information.

## Key Skills Demonstrated

- Cisco IOS Configuration
- SNMPv2c Configuration & Troubleshooting
- GNS3 Network Simulation
- Zabbix Network Monitoring
- Ubuntu Linux Administration
- MySQL Database Management
- Apache & PHP Configuration
- TCP/IP Networking
- SNMP Polling & OID Fundamentals
- Network Performance Monitoring


<div>
  <img width="896" height="366" alt="image" src="https://github.com/user-attachments/assets/e59260ac-c223-4918-9439-267665267062" />
</div>

<div>
  <img width="1300" height="162" alt="image" src="https://github.com/user-attachments/assets/a3256106-20f4-4e22-85b1-4b210ef0b4d2" />
</div>

<div>
  <img width="1600" height="136" alt="image" src="https://github.com/user-attachments/assets/d8584662-e98e-44e5-83fd-92e62f4a29b3" />
</div>

<div>
  <img width="1600" height="781" alt="image" src="https://github.com/user-attachments/assets/ae91687e-2fa5-4f07-af88-6755c36be945" />
</div>

<div>
  <img width="1600" height="795" alt="image" src="https://github.com/user-attachments/assets/0ce5f621-3063-4e9f-83f2-51c7e9af11f0" />
</div>
