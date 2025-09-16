# BASIC-HOME-NETWORK-
# 🏡 Building a Simulated Home Network on Cisco Packet Tracer

This project demonstrates how to set up and configure a simple home network using Cisco Packet Tracer.  
It covers both **wired and wireless connectivity**, DHCP configuration, router setup, and device testing.

---

## 📌 Steps Taken 

### 1. Planned the Network Layout
- Designed a basic home setup including:
  - Wireless Router (Linksys WRT300N)
  - PC to simulate a webcam
  - Laptop for wireless testing
  - Smartphone (optional realism)

### 2. Selected Devices
- **Wireless Router** → Linksys WRT300N  
- **PC** → Used to simulate a webcam (wired)  
- **Laptop** → Tested wireless connectivity  
- **Smartphone** → Added realism to the network  

### 3. Configured the Wireless Router
- Set **SSID**: `HomeNetwork`  
- Enabled **WPA2-PSK encryption**  
- Configured passphrase: `mypassword` *(for demo purposes)*  
- Configured LAN settings for IP addressing and connectivity  

### 4. Enabled DHCP
- Allowed devices to automatically obtain IP addresses  
- Ensured seamless communication within the network  

### 5. Simulated the Webcam Connection
- Connected a PC via **Copper Straight-Through Cable** (wired)  
- Connected a laptop wirelessly to the router  
- Assigned both devices to the same SSID and confirmed connectivity  

### 6. Tested Network Connectivity
- Used the `ping` command to confirm communication:
  - Device ↔ Router  
  - Device ↔ Device within the LAN  

### 7. Added Realism
- Included a **smartphone** to reflect a modern home setup with multiple connected devices  

---

## ✅ Conclusion
This simulation provided a clear, practical understanding of how to configure and secure a small home network.  
It involved:
- Wired and wireless connectivity  
- DHCP management  
- Real-time device communication  

Such setups form the **foundation of modern smart homes**.

---

## 🔐 Security Note
For demonstration, the same password (`mypassword`) was used across all devices.  
⚠️ In real-world scenarios:  
- Always use **strong, unique passwords** for network security  
- Regularly update router firmware and Wi-Fi security settings  

---

## 📂 Files in This Project
- `basic-home-network.pkt` → Packet Tracer topology  
- `router-config.txt` → Router CLI configuration  
- `notes.md` → Concept summary  

---

## 🚀 Learning Outcomes
- Configure a wireless router in Packet Tracer  
- Apply DHCP for automatic IP addressing  
- Connect devices via wired and wireless methods  
- Test network communication with `ping`
