# Azure VM Backup & Recovery Lab

## 📌 Overview
This project demonstrates how to configure and manage Azure VM backups using Recovery Services Vault. It includes backup policy setup, backup execution, restore point verification, and recovery workflow.

---

## 🏗️ Architecture
- Azure Virtual Machine (vm-backup-01)
- Virtual Network (vnet-backup-lab)
- Recovery Services Vault (rsv-backup-lab)
- Backup Policy (Daily)
- Restore Points

---

## ⚙️ Steps Performed
1. Created Resource Group
2. Configured Virtual Network and Subnet
3. Deployed Virtual Machine
4. Created Recovery Services Vault
5. Enabled Backup for VM
6. Applied Backup Policy
7. Triggered Backup Job
8. Verified Backup Status
9. Reviewed Restore Points
10. Configured Restore Options

---

## 📸 Screenshots
All implementation steps are documented in the `/screenshots` folder.

---

## 🧠 Key Learnings
- Difference between snapshot and vault backup
- Application-consistent backups
- Backup policy and retention behavior
- Restore workflow (VM vs disk restore)
- Azure UI differences between VM and Vault views

---

## 🛠️ Skills Demonstrated
- Azure Virtual Machines
- Azure Backup
- Recovery Services Vault
- Disaster Recovery Concepts
- Azure Networking

---

## 🚀 Outcome
Successfully implemented and validated a complete Azure VM backup and recovery solution.
