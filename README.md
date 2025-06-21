#📡 CSC230 Computer Networks Project — MIU (Spring 2025)
This repository contains the full implementation of the Computer Networks Project (CSC230) at Misr International University (MIU), developed under the supervision of Dr. Yasmin Alkady.

Course: CSC230 – Computer Networks Faculty: Computer Science, MIU Team Leader: Diaa Eldeen — 2023/06246 Semester: Spring 2025 Section: Dr. Yasmin Alkady's Groups

📘 Project Overview The project focuses on designing, implementing, and configuring a complex enterprise network with full functionality, security, and management features. It aims to simulate a real-world scenario, including subnetting, routing, VLANs, DHCP, NAT, VPN, wireless access, and full documentation.

✅ Project Objectives VLSM Design – Design and implement a subnetting scheme using 10.0.0.0/8

Network Setup – Configure interfaces, device settings, and IP addressing

Layer 2 Configuration – VLANs, trunking, inter-VLAN routing, EtherChannel

Routing Protocols – Implement OSPFv2, EIGRP, and route redistribution

DHCP Configuration – Set up centralized and remote DHCP servers

NAT – Implement both dynamic (PAT) and static NAT

Network Management – NTP, Syslog, DNS, Web & Mail servers

IPsec VPN – Secure connectivity between remote sites via site-to-site VPN

Wireless Configuration – Deploy a wireless home router with secure access

Connectivity Testing – Full network ping, traceroute, routing table validation

Documentation – Comprehensive guide with screenshots, configs, and test cases

🧰 Technologies & Tools Cisco Packet Tracer

IPv4 Subnetting (VLSM)

OSPFv2 & EIGRP Routing

DHCP, NAT, VLANs

Syslog, NTP, DNS, Email/Web Servers

Site-to-Site IPsec VPN

Wireless Router Configuration

Linux CLI & Network Utilities

📂 Structure /configs/ – Router and switch configuration files

/diagrams/ – Network topologies and addressing schemes

/documentation/ – Final report with testing and verification

/screenshots/ – Ping tests, interface status, and routing tables

/dhcp-nat-vpn/ – DHCP pools, NAT settings, VPN configs

📎 Notes All IP addresses, VLAN IDs, and routing protocols are configured according to project specifications.

The DHCP and static configurations ensure hosts can access the network reliably.

Dynamic routing and route redistribution allow seamless integration of different protocols.

A site-to-site VPN secures communication between MIU and its branch network.

📄 License This project is created for academic purposes and is licensed under the MIT License.
