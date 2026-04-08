# enterprise-network-project

=======
# 🏢 Enterprise Network Project – NovaTech Solutions

## 📌 Overview

This project simulates a real-world enterprise network for a multi-site company with a headquarters, branch office, and data center.

The goal was to design and implement a secure, scalable network using industry-standard technologies.

---

## 🎯 Objectives

* Design a multi-site network (HQ, Branch, Data Center)
* Implement VLAN segmentation
* Configure inter-VLAN routing
* Deploy OSPF for dynamic routing
* Apply ACLs for security
* Configure NAT for internet access

---

## 🧱 Network Design

* HQ (Johannesburg): HR, Finance, IT, Sales departments
* Branch (Cape Town): Admin, Sales
* Data Center: Web, DNS, File servers

---

## 🛠️ Technologies Used

* Cisco Packet Tracer
* VLANs
* OSPF
* ACL (Access Control Lists)
* NAT

---

## 🌐 IP Addressing

| Location    | Network         |
| ----------- | --------------- |
| HQ          | 192.168.10.0/24 |
| Branch      | 192.168.20.0/24 |
| Data Center | 192.168.30.0/24 |

---

## 🔐 Security Implementation

* VLAN segmentation between departments
* ACL rules restricting inter-department access
* IT VLAN has full access
* NAT configured for external communication

---

## 🧪 Testing & Validation

* Successful ping between allowed VLANs
* Blocked traffic between restricted VLANs
* Connectivity to Data Center servers verified

---

## 🚧 Challenges Faced

* OSPF neighbor issues due to incorrect network statements
* VLAN misconfiguration on trunk ports
* ACL rules blocking unintended traffic

---

## 📈 Key Takeaways

* Gained hands-on experience with enterprise network design
* Improved troubleshooting skills
* Learned how to implement network security controls

---

