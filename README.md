
# 🏢 Enterprise Network Simulation – NovaTech Solutions

## 📌 Overview

I designed and implemented a multi-site enterprise network simulating a real company environment with a Headquarters, Branch Office, and Data Center.

The project focuses on network segmentation, secure communication, and dynamic routing using industry-standard technologies.

---

## 🎯 Objectives

* Design a scalable multi-site network
* Segment departments using VLANs
* Enable inter-VLAN communication
* Implement dynamic routing using OSPF
* Enforce security using extended ACLs

---

## 🧱 Network Architecture

* **HQ (Johannesburg):** HR, Finance, IT, Sales
* **Branch (Cape Town):** Admin, Sales
* **Data Center (Midrand):** Web, File, DNS Servers

---

## 🛠️ Technologies Used

* Cisco Packet Tracer
* VLANs (Segmentation)
* Inter-VLAN Routing (Router-on-a-Stick)
* OSPF (Dynamic Routing)
* Extended ACLs (Security Enforcement)

---

## 🌐 IP Addressing

| Network         | Purpose      |
| --------------- | ------------ |
| 192.168.10.0/24 | HR           |
| 192.168.20.0/24 | Finance      |
| 192.168.30.0/24 | IT           |
| 192.168.40.0/24 | Sales        |
| 192.168.50.0/24 | Branch Admin |
| 192.168.60.0/24 | Branch Sales |
| 192.168.70.0/24 | Data Center  |

---

## 🔐 Security Implementation

* VLAN-based segmentation between departments
* Extended ACLs to restrict unauthorized access
* IT VLAN granted full network access
* Controlled communication between departments

---

## 🌍 Routing

* OSPF (Area 0) used for dynamic routing
* Automatic route learning between HQ, Branch, and Data Center
* Scalable and efficient routing design

---

## 🧪 Testing & Validation

* Inter-VLAN communication successful
* OSPF neighbor adjacency established
* End-to-end connectivity verified
* ACL rules correctly blocking and allowing traffic

---

## 📸 Key Screenshots

https://www.notion.so/Packet-Tracer-Project-33c2f9b6c931808d9f6cf89d715df4a5?source=copy_link

### Network Topology
### VLAN Configuration
### OSPF Routing
### ACL Security
### Testing

---

## 🚧 Challenges & Solutions

* OSPF adjacency issues due to missing WAN configuration → resolved by configuring serial interfaces
* VLAN communication issues due to trunk misconfiguration → corrected trunk ports
* ACL rule ordering initially blocked valid traffic → fixed rule sequence

---

## 📈 Key Takeaways

* Practical experience in enterprise network design
* Strong understanding of segmentation and security
* Hands-on troubleshooting of real networking issues
* Ability to simulate real-world infrastructure

---
