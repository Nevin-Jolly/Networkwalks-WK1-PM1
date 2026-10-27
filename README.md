# Week 1 – Cybersecurity Lab Setup

## 📌 Internship Task
**Task:** WK1-PM1 – Project Module 1  
**Topic:** Lab Setup – VirtualBox & Kali Linux  
**Internship:** Cybersecurity Internship at Networkwalks  
**Mentor:** Waqas Karim

## 🎯 Objective

Set up a basic cybersecurity testing lab environment using **Oracle VirtualBox** and **Kali Linux** for cybersecurity and ethical hacking practice.

## 🛠️ Lab Requirements

- VirtualBox as the virtualization platform
- Kali Linux as the attacking/security testing machine
- NAT Network configured with the `10.0.0.0/24` subnet
- Kali Linux configured with IP address `10.0.0.2/24`
- Full Internet access from Kali Linux
- Clipboard sharing enabled
- File drag-and-drop enabled
- Host `/downloads` folder shared with the Kali VM
- VM snapshot created after setup

## 🌐 Network Configuration

| Setting | Configuration |
|---|---|
| Network Type | NAT Network |
| Subnet | `10.0.0.0/24` |
| Kali Linux IP | `10.0.0.2/24` |
| Kali Role | Attacking / Security Testing Machine |
| Internet Access | Enabled |

The lab architecture uses VirtualBox as the base platform, with Kali Linux connected to the custom NAT Network.

## 🔧 Setup Process

### 1. Install 7-Zip
Installed 7-Zip for handling compressed VM files.

### 2. Install VirtualBox
Installed Oracle VirtualBox on the host system.

### 3. Configure NAT Network
Created a custom NAT Network using the `10.0.0.0/24` subnet.

### 4. Import Kali Linux
Downloaded and imported the Kali Linux virtual machine into VirtualBox.

### 5. Configure Kali Linux
Configured the Kali VM to use the NAT Network and assigned:

```text
IP Address: 10.0.0.2/24
```

### 6. Enable VM Integration Features
Configured the VM to support:

- Shared Clipboard
- File Drag & Drop
- Shared Folder: `/downloads`

### 7. Verify Connectivity
Verified that the Kali Linux VM has Internet connectivity through the configured NAT Network.

### 8. Create VM Snapshot
Created a snapshot of the configured Kali Linux VM for recovery and future lab activities.

## 📸 Screenshots

### VirtualBox NAT Network
<img width="1917" height="1078" alt="image" src="https://github.com/user-attachments/assets/7f220051-c250-4020-b949-00d418595e30" />


### Kali Linux Virtual Machine
<img width="1751" height="960" alt="image" src="https://github.com/user-attachments/assets/a090b43d-6f44-43d0-a476-d4a942e39dab" />


### Kali IP Configuration
<img width="1748" height="960" alt="image" src="https://github.com/user-attachments/assets/31db9a5d-6ec1-46ab-888b-a783edd5240d" />


### Internet Connectivity
<img width="1748" height="950" alt="image" src="https://github.com/user-attachments/assets/cb4055a5-2164-4eb0-9356-45f406050552" />



## 📚 What I Learned

- Basics of virtualization using VirtualBox
- Setting up a cybersecurity testing environment
- Configuring a NAT Network
- Assigning a static IP address to a Linux VM
- Connecting a virtual machine to the Internet
- Configuring VirtualBox integration features
- Preparing a controlled environment for cybersecurity and ethical hacking practice

## 🚀 Next Steps

The lab can later be expanded with additional virtual machines such as Windows systems and Android environments for isolated cybersecurity practice, connectivity testing, and future CTF/lab challenges.

## 👨‍💻 Internship

This task was completed as part of my **Cybersecurity Internship at Networkwalks**, under the guidance of **Waqas Karim**.

---

**Week 1 | Cybersecurity Internship | Networkwalks**
