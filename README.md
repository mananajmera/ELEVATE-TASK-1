# ELEVATE-TASK-1
# 🛰️ Network Scan using Nmap on Kali Linux

## 🔍 Overview

This project documents a network scan performed on the subnet `192.168.81.0/24` using the powerful and versatile `nmap` tool on **Kali Linux**. The objective was to discover live hosts, open ports, running services, and potential vulnerabilities in the local network for learning and analysis purposes.


## 🛠️ Tools Used

- **Kali Linux** (2025.1)
- **Nmap** (Network Mapper) - Version 7.95

---

## 🌐 Target Network

- **Subnet:** `192.168.81.0/24`
- **IP Range:** `192.168.81.1` to `192.168.81.254`

---

## 📋 Scan Commands & Description

### 1. 🔎 **Host Discovery (Ping Sweep)**
sudo nmap -sn 192.168.81.0/24
### 2. 🔎 **Full TCP SYN scan on all ports (1-65535)**
sudo nmap -p- -sS 192.168.81.0/24

