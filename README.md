# 📡 CSC230 Computer Networks Project — MIU (Spring 2025)

This repository contains the full implementation of the Computer Networks Project for **CSC230 – Computer Networks** at **Misr International University (MIU)**.  
Developed under the supervision of **Dr. Mostafa Abdelrahman**.

- **Course:** CSC230 – Computer Networks  
- **Faculty:** Computer Science, MIU  
- **Team Leader:** Mariam Mohamed  
- **Semester:** Spring 2025  
- **Section:** Dr. Mostafa Abdelrahman  

---

## 📘 Project Overview

The project focuses on **designing, implementing, and configuring a complex enterprise network** that reflects real-world scenarios. The network ensures **functionality, security, and manageability** across different services.

Main network features include:

- Subnetting using VLSM  
- Layer 2/3 configurations  
- Dynamic routing protocols  
- Network services: DHCP, NAT, DNS, Web & Mail  
- IPsec VPN between remote sites  
- Wireless router setup  
- Full testing and documentation

---

## ✅ Project Objectives

- **VLSM Design:** Implement a subnetting scheme using `10.0.0.0/8`
- **Network Setup:** Interface configuration and IP addressing
- **Layer 2 Config:** VLANs, trunking, inter-VLAN routing, EtherChannel
- **Routing Protocols:** Configure OSPFv2, EIGRP, and route redistribution
- **DHCP:** Centralized and remote DHCP servers
- **NAT:** Dynamic (PAT) and Static NAT implementation
- **Network Management:** NTP, Syslog, DNS, Web & Mail servers
- **VPN:** Secure site-to-site IPsec VPN setup
- **Wireless:** Configure wireless home router with WPA2 security
- **Testing:** Verify using ping, traceroute, routing tables
- **Documentation:** Final report with diagrams, screenshots, and configs

---

## 🧰 Technologies & Tools

- **Cisco Packet Tracer**
- **IPv4 Subnetting (VLSM)**
- **OSPFv2 & EIGRP Routing**
- **DHCP & NAT**
- **VLANs, Trunking, EtherChannel**
- **Syslog, NTP, DNS**
- **Email & Web Servers**
- **IPsec VPN (Site-to-Site)**
- **Wireless Router Configuration**
- **Linux CLI & Network Utilities**

---

## 📂 Project Structure

```
/configs/         → Router and switch configuration files  
/diagrams/        → Network topologies and addressing plans  
/documentation/   → Final report with test cases and verification  
/screenshots/     → Interface status, pings, and routing outputs  
/dhcp-nat-vpn/    → DHCP pools, NAT settings, VPN configs  
```

---

## 📎 Notes

- All IP addresses, VLANs, and protocols follow the assigned project specification.
- Reliable host access is ensured using DHCP and static IP configurations.
- Route redistribution enables seamless protocol integration.
- Site-to-site VPN secures communication between MIU and branch sites.

---

## 📄 License

This project is licensed under the **MIT License** and is intended for **academic use only**.
