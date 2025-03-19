# 🖧 Computer Network Topology & Configuration Project

This repository contains a **Computer Network project** focused on building and configuring network topologies using **Packet Tracer** and performing network analysis using **Wireshark**.

## 📜 Project Overview:
This project covers key areas in **network configuration**, **IP subnetting**, and **routing protocols**. The main objectives are:
1. Learn how to use **Packet Tracer** for network configuration.
2. Implement **IP subnetting** and address assignment.
3. Configure end devices like **PCs** and **servers**.
4. Implement **routing protocols** on routers.
5. Perform **network testing** and **debugging**.

## 📑 Parts of the Project:
### **Part 1: Wireshark Packet Analysis**
Using Wireshark, capture and analyze **TCP**, **DHCP**, and **ICMP** packets. Explain at least **4 fields** in each type of packet captured.

### **Part 2: Packet Tracer Network Configuration**
1. **IP Subnetting & Address Assignment:**
   - Subnetting and assigning IP addresses for various subnets (Data Center, Companies A/B/C) based on the provided student ID. Example: 1212031 → IP: 103.82.4.0/23.
   - Include a subnet table showing **network IP**, **broadcast IP**, **first IP**, **last IP**, and **maximum number of IPs**.

2. **Network Topology Construction:**
   - Build the network topology as shown in the provided figure using **Packet Tracer**.
   - Configure routers and **end devices** (PCs & servers) with static IPs.
   - Configuration details for each network:
     - **Data Center**: 2 servers and 1 switch.
     - **Company A**: 3 PCs and 1 switch.
     - **Company B**: 2 PCs, 1 server, and 1 switch.
     - **Company C**: 2 offices, each with PCs and switches.
     - **Core**: 5 routers.

3. **Server Configuration:**
   - Configure three servers: **HTTP/WEB** server, **DNS** server, and **Mail** server.
   - Set the DNS and WEB servers with domain name `www.ENCS3320.com`.
   - Modify the `index.html` to include group names, IDs, and a **“Welcome to Computer Networks course”** message (with part of the phrase in red).

4. **Routing Protocols:**
   - Implement **OSPF** (Open Shortest Path First) on all routers to allow communication between subnets.

5. **Testing & Troubleshooting:**
   - Test connectivity between all **PCs** using **ping** and **tracert** commands. Capture snapshots of the results.
   - Ensure **HTTP access** to the website `www.ENCS3320.com` from all PCs, and capture snapshots for testing.

## 📊 Results:
- **Snapshots** of the network configurations, **ping** and **tracert** tests.
- **Wireshark captures** for TCP, DHCP, and ICMP packets.
- **Packet Tracer configurations** for routers, switches, and end devices.

## 📂 Files Included:
- **📄 Report (PDF)**: Contains detailed explanations, configurations, results, and troubleshooting steps.
- **💾 Packet Tracer Project (`.pkt`)**: Includes the network topology and device configurations.
- **📷 Screenshots**: Show snapshots for **ping**, **tracert**, **Wireshark** captures, and **website access** tests.

## 🚀 How to Run:
1. **Open the `.pkt` file** in Packet Tracer to view and interact with the network topology.
2. **Run tests** like **ping**, **tracert**, and access the website from each PC.
3. **Follow the instructions in the PDF** to understand the configuration, testing, and troubleshooting steps.

This project covers **network setup**, **troubleshooting**, and **routing protocol configuration**, providing a hands-on experience with modern networking tools and protocols.
