# Virtual Private Networks Lab 

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
<img width="1028" height="391" alt="T22" src="https://github.com/user-attachments/assets/0b7f356d-b75b-4c78-86f0-3bac72818ebc" />

**Observation:** VM deployed successfully in Azure.

---

### 2. Preparing to access VPN Software (Proton VPN)
<img width="1252" height="812" alt="T23" src="https://github.com/user-attachments/assets/a3b75952-e04f-453e-a322-854793d18e09" />

**Observation:** VPN client ready to install.

---

### 3. IP Address Before Launching VPN
<img width="531" height="576" alt="VMIP" src="https://github.com/user-attachments/assets/967042d4-7f40-4baf-aa02-29f222a2a2f1" />

**Observation:** Verified original public IP of VM.

---

### 4. Securing VPN Connection (Netherlands Server)
<img width="1252" height="802" alt="T24" src="https://github.com/user-attachments/assets/15bf3037-8412-4a1f-b947-e483462b6c09" />

**Observation:** VPN connection successfully established.

---

### 5. New IP Address Under Secured VPN
<img width="577" height="612" alt="VPN" src="https://github.com/user-attachments/assets/78228465-4b93-48dd-ac09-3415f08abbb7" />

**Observation:** Public IP masked by VPN; secure connection verified.

</details>

---

## Lessons Learned

- VPNs can effectively **mask public IP addresses**.  
- Azure VMs provide a **controlled environment** for testing network security.  
- Understanding **IP changes** is crucial for secure network access.  
- VPN client setup and testing is straightforward when following step-by-step lab procedures.  
