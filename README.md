# 🚀 SDN Network Utilization Monitor using Mininet

## 📌 Project Overview
This project demonstrates a Software Defined Networking (SDN) based network using Mininet. It monitors network traffic, applies flow rules, blocks specific traffic (ICMP), and analyzes bandwidth utilization using tools like iperf and Wireshark.

---

## 🎯 Objectives
- Create a custom network topology using Mininet
- Implement SDN controller-based flow rules
- Monitor network utilization
- Block ICMP (ping) traffic
- Analyze traffic using Wireshark
- Measure bandwidth using iperf

---

## 🛠️ Tools & Technologies Used
- Mininet
- Ryu Controller
- OpenFlow Protocol
- Wireshark
- iperf
- Python

---

## 🌐 Network Topology
This shows the structure of hosts and switches in the network.

![Topology](screenshots/topology.png)

---

## 🎮 Controller Execution
Ryu controller managing the network and installing flow rules.

![Controller](screenshots/controller.png)

---

## 🔄 Flow Table Rules
Flow entries installed in switches by the controller.

![Flows](screenshots/flows.png)

---

## 📡 Ping Test (Connectivity Check)
All hosts successfully communicate with each other.

![Ping All](screenshots/pingall.png)

---

## 🚫 Blocking ICMP Traffic
Ping between hosts is blocked using flow rules.

![Blocked Ping](screenshots/blocked_ping.png)

---

## 📊 Bandwidth Measurement using iperf
TCP traffic test to measure throughput between hosts.

![Iperf](screenshots/iperf_tcp.png)

---

## 📈 Network Utilization Monitoring

### Before Traffic
Network usage before generating traffic.

![Before](screenshots/utilization_before.png)

### During Traffic
Network usage during heavy traffic.

![During](screenshots/utilization_during.png)

---

## 🔍 Packet Analysis using Wireshark

### ICMP Traffic Capture
Normal ICMP packets observed.

![Wireshark ICMP](screenshots/wireshark_icmp.png)

### Blocked Traffic Capture
No ICMP packets observed after blocking.

![Wireshark Block](screenshots/wireshark_block.png)

---

## ⚙️ Features Implemented
- Custom SDN topology
- Dynamic flow rule installation
- ICMP traffic blocking
- Real-time network monitoring
- Bandwidth analysis
- Packet-level inspection

---

## 📌 Conclusion
This project successfully demonstrates how SDN can control and monitor network behavior dynamically. It shows how traffic can be managed, analyzed, and restricted efficiently using a centralized controller.

---

## 📂 Project Structure
project/
│── README.md
│── screenshots/
│     ├── topology.png
│     ├── controller.png
│     ├── flows.png
│     ├── pingall.png
│     ├── blocked_ping.png
│     ├── iperf_tcp.png
│     ├── utilization_before.png
│     ├── utilization_during.png
│     ├── wireshark_icmp.png
│     ├── wireshark_block.png
```
