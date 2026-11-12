# 🔐 Cybersecurity Lab Environment Setup

### Setting Up Kali Linux on Oracle VirtualBox

<p align="center">
  <img src="https://img.shields.io/badge/VirtualBox-7.2-blue?style=for-the-badge&logo=virtualbox">
  <img src="https://img.shields.io/badge/Kali_Linux-2026.2-black?style=for-the-badge&logo=kalilinux">
  <img src="https://img.shields.io/badge/Focus-Cybersecurity-red?style=for-the-badge">
  <img src="https://img.shields.io/badge/Networking-Configuration-green?style=for-the-badge">
</p>

## 📌 Overview

This project documents the setup of a virtual cybersecurity lab using **Oracle VirtualBox and Kali Linux**. The environment provides an isolated platform for learning Linux, networking, and ethical hacking.

## ⚙️ Setup Process

1. **Install VirtualBox:** Download and install Oracle VirtualBox to create and manage virtual machines.
2. **Install Kali Linux:** Download the Kali Linux virtual machine image and import it into VirtualBox.
3. **Configure Resources:** Allocate RAM, CPU cores, and storage to the virtual machine.
4. **Configure Networking:** Set the network adapter to NAT to allow Kali Linux to access the internet through the host machine.
5. **Start Kali Linux:** Boot the virtual machine and verify that the operating system is running correctly.

## 🌐 Internet Connectivity Testing

To ensure Kali Linux can access the internet:

**Check the network interface:**

```bash
ip addr
```

**Test internet connectivity:**

```bash
ping -c 4 8.8.8.8
```

**Test DNS resolution:**

```bash
ping -c 4 google.com
```

If the IP address responds but the domain name does not, check the DNS configuration.

## 🛠️ Technologies Used

- Oracle VirtualBox 7.2
- Kali Linux
- NAT Networking
- Linux Terminal

## 📸 Lab Screenshots

Screenshots of the VirtualBox configuration, Kali Linux environment, and successful internet connectivity tests.

## ✅ Outcome

Successfully established a Kali Linux virtual machine using VirtualBox, configured network connectivity, and verified internet access.

---

<p align="center">
  <b>Learning by building. Exploring cybersecurity one step at a time. 🔐</b>
</p>
