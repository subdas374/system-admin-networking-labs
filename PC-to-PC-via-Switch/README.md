# Practical 1: Connect 2 PCs with a Switch

## 🖥️ Topology
![Screenshot](https://github.com/subdas374/system-admin-networking-labs/blob/main/PC-to-PC-via-Switch/screenshots/Screenshot.png)

PC1 ---- Switch ---- PC2




## ⚙️ IP Configuration
### PC1
- IP Address: `192.168.1.10`
- Subnet Mask: `255.255.255.0`
- Default Gateway: *(Not needed in this lab)*

### PC2
- IP Address: `192.168.1.20`
- Subnet Mask: `255.255.255.0`
- Default Gateway: *(Not needed in this lab)*

---

## 🔧 Steps
1. Drag 2 PCs and 1 Switch into Packet Tracer.  
2. Connect **PC1 → Switch** and **PC2 → Switch** using **Copper Straight-Through** cables.  
3. Assign IP addresses as shown above in the **Desktop → IP Configuration** tab of each PC.  
4. Open **Command Prompt** on PC1 and run:
   ```bash
   ping 192.168.1.20
