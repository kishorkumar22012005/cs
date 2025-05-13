# cs
# 🔍 Install Metasploitable on VirtualBox and Search for Unpatched Vulnerabilities

This project demonstrates how to set up the **Metasploitable vulnerable VM** using **VirtualBox** and identify unpatched vulnerabilities using tools like **Nmap**, **Nikto**, and **Metasploit Framework**.

## 🎯 Objective

To simulate a vulnerable environment for penetration testing and ethical hacking practice. You'll learn how to:
- Deploy Metasploitable on VirtualBox
- Scan and identify open ports
- Enumerate services and detect vulnerabilities
- Use Metasploit to exploit known unpatched issues

---

## 🧰 Tools & Requirements

- **VirtualBox** (latest version)
- **Metasploitable 2 VM** (OVA or VMDK)
- **Kali Linux / Parrot OS** (optional for attacker machine)
- **Nmap**
- **Nikto**
- **Metasploit Framework**
- Minimum 4GB RAM and 20GB disk space

---

## 🚀 Installation Steps

### 1. Install VirtualBox
Download and install from:  
[https://www.virtualbox.org/wiki/Downloads](https://www.virtualbox.org/wiki/Downloads)

### 2. Download Metasploitable 2
Get from the official repository or trusted sources like:
- [https://sourceforge.net/projects/metasploitable/](https://sourceforge.net/projects/metasploitable/)

### 3. Import Metasploitable into VirtualBox
1. Open VirtualBox → File → Import Appliance
2. Select the `.ova` or `.vmdk` file
3. Configure network to **Host-Only Adapter** or **Internal Network**

### 4. Boot Up Metasploitable
- Default login: `msfadmin` / `msfadmin`

---

## 🔎 Scanning for Vulnerabilities

### Step 1: Find the IP Address
```bash
ifconfig
