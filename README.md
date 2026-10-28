# M-UBAID-Week-1-Internship-Network-Walks
<div align="center">

# 🔐 Cybersecurity Lab Environment Setup



#  Linux Network Configuration Lab

### Week 01 | Network Walks IT Trainers Internship

![Linux](https://img.shields.io/badge/Linux-OS-FCC624?style=flat&logo=linux&logoColor=black)
![VirtualBox](https://img.shields.io/badge/VirtualBox-Virtualization-183A61?style=flat&logo=virtualbox)
![Networking](https://img.shields.io/badge/Networking-Fundamentals-blue?style=flat)

##  Overview
This lab involved setting up a Linux virtual machine in Oracle VirtualBox, configuring a manual IPv4 address, enabling NAT networking, and testing internet connectivity.

##  Objectives
- Set up Linux in VirtualBox.
- Configure a manual IP address in the `10.0.0.0/24` subnet.
- Configure NAT networking.
- Verify internet connectivity.

## Tools Used
- Kali Linux
- Oracle VirtualBox
- Linux Terminal
- IPv4, NAT, and DNS

##  Implementation Steps

1. **Install Linux:** Created and started a Linux virtual machine in VirtualBox.
2. **Configure Networking:** Enabled the virtual network adapter and selected NAT mode.
3. **Assign IP Address:** Configured a manual IPv4 address within the required subnet.
4. **Check Configuration:** Used Linux commands to inspect the network interface and routing table.
5. **Test Connectivity:** Tested external IP connectivity and DNS resolution.

##  Verification Commands

```bash
ip addr
ip route
cat /etc/resolv.conf
ping -c 4 8.8.8.8
ping -c 4 google.com
```

##  Learning Outcomes
- Understanding IPv4 addressing and CIDR notation.
- Learning how NAT provides network access to virtual machines.
- Understanding default gateways and DNS.
- Practicing basic Linux network troubleshooting.

##  Conclusion
Successfully practiced Linux virtual machine setup and fundamental networking configuration as part of my Week 01 remote internship task.

---
**Program:** Network Walks IT Trainers Internship  
**Task:** Week 01 — Linux Network Configuration
 
