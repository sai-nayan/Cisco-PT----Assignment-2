# Cisco-PT----Assignment-2
# Packet Flow Visualization Using Simulation Mode

## 📘 Course Details
- **Course Code:** ENCS304  
- **Course Name:** Computer Networks  
- **Program:** B.Tech CSE (AI/ML, DS, Cyber, FSD, UX/UI)

---

## 🎯 Objective
To understand how packets flow in a LAN using Cisco Packet Tracer Simulation Mode by observing:
- ARP request and reply
- ICMP echo request and reply
- Switch MAC address learning

---

## 🛠️ Tools Used
- Cisco Packet Tracer

---

## 🌐 Network Topology
- 1 Switch (2960)
- 3 PCs (PC0, PC1, PC2)
- IP Range: 192.168.20.1 – 192.168.20.3 /24

---

## 🧪 Experiment Steps

### 1. First Ping (PC0 → PC1)
- ARP Request (Broadcast)
- ARP Reply (Unicast)
- ICMP Echo Request
- ICMP Echo Reply

### 2. Second Ping (PC0 → PC1)
- Only ICMP packets observed
- No ARP (cached)

### 3. MAC Table Learning
- Switch learns MAC addresses dynamically
- Stores MAC-to-port mapping

---

## 📊 Observations

- First ping is slower due to ARP resolution  
- Second ping is faster due to cached MAC address  
- Switch builds MAC table by observing incoming frames  

---

## 📁 Files Included

- `exp2_packetflow.pkt` → Packet Tracer file  
- `output_exp2.txt` → Observations  
- `report_exp2.pdf` → Screenshots + explanation  
- `README.md` → Documentation  

---

## 🚀 Applications
- Helps in network troubleshooting  
- Explains delay in first ping  
- Useful for understanding switching behavior  

---

## ✅ Conclusion
The experiment successfully demonstrates ARP resolution, ICMP communication, and switch MAC learning behavior using Simulation Mode in Cisco Packet Tracer.
