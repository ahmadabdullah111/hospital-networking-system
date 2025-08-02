# 🏥 Hospital Networking System

This project presents a comprehensive network infrastructure design for a hospital, built using Cisco Packet Tracer. It is ideal for medium to large-scale healthcare facilities aiming to ensure secure, efficient, and scalable communication across all departments.

---

## 📌 Objective

The goal of this project is to design a hospital's internal network that ensures:
- **Smooth communication** between departments
- **High availability** and **minimal downtime**
- **Security segmentation** using VLANs
- Centralized network control using routers and switches

---

## 🧱 Network Architecture Overview

### 🧩 Core Components:
- **Departments Covered**: Emergency, ICU, OPD, Pharmacy, Administration
- **Network Devices**: Routers, Switches (Layer 2 and 3), Wireless Access Points
- **End Devices**: PCs, Printers, Servers
- **Protocols Used**: DHCP, DNS, VLAN, Static & Dynamic Routing

### 🔐 Security Features:
- VLAN configuration to isolate departments
- Basic ACL (Access Control List) setup
- Default gateway protections

---

## 📊 IP Addressing Scheme

Each department is assigned a separate subnet, e.g.:
- Emergency: `192.168.10.0/24`
- ICU: `192.168.20.0/24`
- Pharmacy: `192.168.30.0/24`
- And so on...

DHCP is configured centrally or per VLAN.

---

## ⚙️ Tools and Technologies Used

| Tool               | Purpose                          |
|--------------------|----------------------------------|
| Cisco Packet Tracer | Network Design & Simulation     |
| Cisco CLI          | Manual Configuration of Devices  |

---

## 📂 File Included

- `Hospital Networking System.pkt` – Main Cisco Packet Tracer project file

---

## 👨‍⚕️ Use Case

This design can be used:
- In academic projects related to computer networking
- For training network engineers in healthcare network setup
- As a base for real-world hospital network implementation

---

## 👨‍💻 Author

**Md Abdullah Talukdar**  
Computer Engineering Student | Networking Enthusiast
