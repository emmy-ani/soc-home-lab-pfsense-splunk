# soc-home-lab-pfsense-splunk

A Security Operations Center (SOC) Home Lab built using VMware, pfSense, Splunk Enterprise, Kali Linux, and Windows 10 to simulate a small enterprise network environment for cybersecurity training and SOC infrastructure deployment.

---

## 📌 Project Overview
This project focuses on designing and deploying a SOC lab environment from scratch. The lab provides a foundation for learning network security, firewall administration, SIEM deployment, log management, and future security monitoring activities.

---

## 🖥️ Lab Components
* **pfSense** (Firewall & Router)
* **Splunk Enterprise** (SIEM)
* **Ubuntu Server** (Host for SIEM)
* **Kali Linux** (Attacker Machine)
* **Windows 10** (Victim Machine)
* **VMware Workstation** (Hypervisor)

---

## 📐 Network Architecture

### IP Addressing Matrix
| Device | IP Address | Role |
| :--- | :--- | :--- |
| **pfSense** | `192.168.56.1` | Firewall / Gateway |
| **Splunk Server** | `192.168.56.10` | SIEM |
| **Kali Linux** | `192.168.56.20` | Attacker Machine |
| **Windows 10** | `192.168.56.30` | Victim Machine |

---

## 🛠️ Technologies Used
* **Virtualization:** VMware Workstation
* **Security & SIEM:** pfSense, Splunk Enterprise
* **Operating Systems:** Ubuntu Server 22.04 LTS, Kali Linux, Windows 10
* **Networking:** NAT, Host-Only Networks, Static IPs

---

## ⚡ Deployment Highlights

### 1. pfSense Configuration
* Deployed dual network interfaces (WAN & LAN).
* Assigned the LAN Gateway to `192.168.56.1`.
* Handled full NAT and Host-Only network segmentation.

### 2. Splunk Deployment
* Installed Splunk Enterprise on a persistent Ubuntu Server.
* Configured static IP addressing layers to avoid network drift.
* Prepared the SIEM platform for future log ingestion and active monitoring.

### 3. Offensive & Defensive Endpoints
* **Kali Linux:** Configured as an attacker workstation and connected to the internal SOC lab network.
* **Windows 10 Endpoint:** Configured as a victim machine and connected to the same internal network segment.

---

## 📂 Project Deliverables
* **📄 Detailed Setup Documentation:** [View Full Lab Setup PDF](SOC_Home_Lab.pdf)
  * *This report includes full virtual machine options, Netplan script parameters, verification commands, and configuration snapshots verifying the lab works perfectly.*

---

## 🧠 Skills Demonstrated
* SOC Infrastructure Deployment & SIEM Installation
* Firewall Administration & Network Configuration
* Hypervisor Virtualization
* Linux & Windows System Administration
* Technical Documentation

---

## 🚀 Future Enhancements
* Windows Event Log Collection & Syslog Integration
* Custom Splunk Dashboards & Security Monitoring Alerts
* Threat Detection Use Cases & Incident Response Scenarios

---

## ✍️ Author
**Joseph Emeka Ani** 
*Cybersecurity | Networking | SOC Operations*
