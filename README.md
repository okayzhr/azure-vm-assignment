# Azure VM Assignment

This project involves creating a Windows Server virtual machine using a free Azure account. All resources are grouped under a single **Resource Group**.

## 🚀 Created Resources
- **Resource Group**: `azure-vm-rg`
- **Virtual Network (VNet)**: `azure-vnet`
- **Subnet**: `default-subnet`
- **Windows Virtual Machine (VM)**: `my-windows-vm`
- **Public IP Address**: Assigned for RDP access
- **Data Disk**: Additional 128 GB disk

---

## 📌 Performed Actions

### 📍 Resource Group Creation
A resource group named **`azure-vm-rg`** was created to manage all related resources in a single place.

### 🌐 Virtual Network and Subnet Configuration
A **Virtual Network (VNet)** and an associated **Subnet** were configured to support the VM:
- Virtual Network name: `azure-vnet`
- Subnet name: `default-subnet`

### 🖥️ Windows Virtual Machine Deployment
A virtual machine with Windows Server 2022 Datacenter was deployed:
- VM Name: `my-windows-vm`
- Region: West Europe
- VM Type: `Standard_B1s (1vCPU, 1GB RAM)` (Free-tier eligible)
- **Public IP Address** assigned for RDP access

### 💾 Attaching an Additional Data Disk
A **128 GB data disk** was added to the virtual machine to extend storage capacity.

### 🔌 Connecting via RDP
- Remote Desktop Protocol (RDP) was used to connect to the virtual machine via its **public IP address**.

### 🗑️ Resource Cleanup (Optional)
To avoid unnecessary costs, all resources were deleted using the **`azure-vm-rg`** resource group.

---

## 📷 Screenshots
Screenshots documenting the setup process are included in this repository.

<img width="1280" alt="image" src="https://github.com/user-attachments/assets/3031e177-99ea-46ef-9f61-22339033ea17" />


<img width="1277" alt="image" src="https://github.com/user-attachments/assets/b0290904-270e-4464-8354-7cb619b5f68b" />


![WhatsApp Image 2025-03-20 at 10 07 18](https://github.com/user-attachments/assets/70abb7f6-0c0a-4dba-85c9-9fc2097a2afb)

---

## 📢 Note
This project was created using **free Azure credits**. If you do not wish to transition to paid services, it is recommended to **delete the resources** after use.
