# Virtual Private Networks Lab – Azure Deployment

This repository documents a **personal lab from my VPN Fundamentals training**, conducted on **Microsoft Azure**. The lab demonstrates **VM deployment, VPN client installation, IP verification, and secure connection testing**.

---

## Table of Contents

1. [Description](#description)
2. [Utilities Used](#utilities-used)
3. [Environment Used](#environment-used)
4. [Program Walk-through: Initiating a VPN Connection](#program-walk-through-initiating-a-vpn-connection)
5. [Lessons Learned](#lessons-learned)

---

## Description

Hands-on labs from my VPN Fundamentals training. Includes **screenshots, step-by-step instructions, and lessons learned**.

---

## Utilities Used

- **Microsoft Azure**  
- **Remote Desktop Connection**  

---

## Environment Used

- **Windows 10 (22H2)**  
- **Virtual Machines**

---

## Program Walk-through: Initiating a VPN Connection

<details>
<summary>View Steps</summary>

### 1. Deployment of Virtual Machine
<img src="https://i.imgur.com/ChrWWrj.png" alt="VM Deployment Successful" style="max-width:100%; height:auto; display:block; margin:auto;" />
**Observation:** VM deployed successfully in Azure.

---

### 2. Preparing to Download VPN Software (Proton VPN)
<img src="https://i.imgur.com/Ex3aVmb.png" alt="Preparing VPN Download" style="max-width:100%; height:auto; display:block; margin:auto;" />
**Observation:** VPN client ready to install.

---

### 3. IP Address Before Launching VPN
<img src="https://i.imgur.com/DU1i3Er.png" alt="IP Before VPN" style="max-width:100%; height:auto; display:block; margin:auto;" />
**Observation:** Verified original public IP of VM.

---

### 4. Securing VPN Connection (Netherlands Server)
<img src="https://i.imgur.com/LRfe2fb.png" alt="VPN Connection Established" style="max-width:100%; height:auto; display:block; margin:auto;" />
**Observation:** VPN connection successfully established.

---

### 5. New IP Address Under Secured VPN
<img src="https://i.imgur.com/dbQANgr.png" alt="IP After VPN" style="max-width:100%; height:auto; display:block; margin:auto;" />
**Observation:** Public IP masked by VPN; secure connection verified.

</details>

---

## Lessons Learned

- VPNs can effectively **mask public IP addresses**.  
- Azure VMs provide a **controlled environment** for testing network security.  
- Understanding **IP changes** is crucial for secure network access.  
- VPN client setup and testing is straightforward when following step-by-step lab procedures.  