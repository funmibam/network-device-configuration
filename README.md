# Cisco Packet Tracer Lab - Network Device Configuration and Connectivity

## Overview
This lab covers various tasks related to configuring and managing network devices in Cisco Packet Tracer. We explored connecting devices using different cables, installing and powering up routers, and configuring network devices through the command-line interface (CLI). We also configured DHCP and static IP addressing to verify connectivity between devices on the network.

## Lab Objectives
- Investigate devices in a wiring closet.
- Connect end devices (PCs and laptops) to networking devices using a console or USB cable.
- Install and configure a backup router.
- Use the Cisco Internetwork Operating System (IOS) to manage and configure devices.
- Enable DHCP on PCs to dynamically receive IP addresses.
- Use the CLI to configure a hostname and perform network troubleshooting.

## Steps Completed

### 1. Connecting a PC to the Router
In the first part of the lab, we connected **PC_1** to the **Edge_Router** using a console cable (RS232) to access the router’s management interface. This involved:
- Connecting the **RS232 port** on **PC_1** to the **Console port** on the **Edge_Router**.
- Accessing the router’s command-line interface (CLI) via **Terminal** software in **PC_1**.

  <img width="557" alt="Screenshot 2024-10-17 050730" src="https://github.com/user-attachments/assets/a13c2b8e-6161-47b8-bb30-87cae6534263">


### 2. Installing and Configuring the Backup Router
Next, we installed a **Backup_Router** from the inventory in the rack:
- Located the **Backup_Router** on the 4th shelf and dragged it into an empty rack space.
- Powered up the **Backup_Router**.
- Connected **Laptop_1** to the **Backup_Router** using a **USB console cable**.
- Accessed the router's **CLI** via terminal software on **Laptop_1**.

### 3. Configuring the Backup Router's Hostname
Using the CLI on the **Backup_Router**, we configured the hostname:
```bash
Router> enable
Router# configure terminal
Router(config)# hostname Edge_Router_Backup
Edge_Router_Backup(config)# end


<img width="365" alt="Screenshot 2024-10-17 054025" src="https://github.com/user-attachments/assets/1acfddc3-9417-4b8e-9c1f-d92c4c43372d">





