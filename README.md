# active-directory-lab
Active Directory Home Lab using Windows Server DNS, and Proxmox
# 🖥️ Active Directory Home Lab (Proxmox)

## 📌 Overview
This project demonstrates the deployment and configuration of a fully functional Active Directory environment using Windows Server in a virtualized lab.

## 🎯 Objectives
- Install and configure Active Directory Domain Services (AD DS)
- Set up DNS for domain resolution
- Create and manage users and groups
- Join a Windows client machine to the domain
- Troubleshoot real-world network and authentication issues

---

## 🏗️ Lab Environment
- Hypervisor: Proxmox VE  
- Server OS: Windows Server  
- Client OS: Windows 11  
- Network: Private LAN (192.168.x.x)  
- DNS: Active Directory Integrated  

---

## ⚙️ Configuration Steps

### 1. Windows Server Setup
- Installed Windows Server VM
- Configured static IP address
- Verified connectivity with ping tests

### 2. Active Directory Domain Services
- Installed AD DS role
- Promoted server to Domain Controller
- Created domain: `eddie.local`

### 3. DNS Configuration
- Verified DNS installation
- Configured server as primary DNS
- Tested domain name resolution

### 4. User & Group Management
- Created Organizational Units (OUs)
- Added users and admin accounts
- Assigned group permissions

### 5. Client Integration
- Joined Windows 11 machine to domain
- Verified domain login
- Tested communication with server

---

## 🧪 Troubleshooting Highlights
- Fixed DNS misconfiguration preventing domain join
- Resolved IP addressing conflicts
- Corrected domain login format (DOMAIN\user)
- Diagnosed one-way ping/network issues

---

## 💡 Skills Demonstrated
- Active Directory Administration
- DNS Configuration
- Virtualization (Proxmox)
- Networking Fundamentals
- IT Troubleshooting

---

## 🚀 Future Improvements
- Group Policy (GPO)
- File sharing + permissions
- Security monitoring (Wazuh)
- Account lockout policies

---

## 📄 Resume Bullet
Built and configured a Windows Server Active Directory environment in a Proxmox virtual lab, including domain controller setup, DNS configuration, user/group management, and Windows client domain integration; troubleshot network and authentication issues to achieve full domain functionality.
