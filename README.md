# 🚀 Config-v2  
### Curated & Manually Tested V2Ray Configurations

![Status](https://img.shields.io/badge/status-active-brightgreen)
![Updates](https://img.shields.io/badge/updates-manual-blue)
![License](https://img.shields.io/badge/license-MIT-yellow)
![Platform](https://img.shields.io/badge/platform-V2Ray-orange)
![Maintenance](https://img.shields.io/badge/maintenance-personal-lightgrey)

A clean, organized, and manually curated collection of **tested V2Ray configurations**.  
This repository is maintained for **personal use and a small group of trusted friends**, ensuring that each configuration is verified before being published.

---

## 📚 Table of Contents
- [About](#about)
- [Features](#features)
- [Repository Structure](#repository-structure)
- [How It Works](#how-it-works)
- [Usage](#usage)
- [Direct Raw Config URLs](#direct-raw-config-urls)
- [Screenshots & Diagrams](#screenshots--diagrams)
- [FAQ](#faq)
- [Troubleshooting](#troubleshooting)
- [Notes](#notes)
- [Contributing](#contributing)
- [Support](#support)

---

## 📌 About

This project provides a set of **working V2Ray configuration files**, manually tested and updated periodically.  
The goal is to offer a simple, reliable, and noise-free source of configs without broken links or expired servers.

This repository is **non-commercial** and intended for **private use only**.

---

## ✨ Features

- ✔️ Manually tested V2Ray configs  
- ✔️ Clean and organized structure  
- ✔️ Updated periodically  
- ✔️ No ads, no tracking, no commercial intent  
- ✔️ Easy to import into any V2Ray client  

---

## 📂 Repository Structure
```bash
Config-v2/
│
├── config/            # V2Ray configuration files
│   ├── MCI.txt
│   ├── IRN.txt
│   └── ...
│
└── README.md          # Project documentation
```

---

## 🔧 How It Works
```bash
+------------------+       +------------------+       +------------------+
|   Find Servers   | --->  |   Manual Test    | --->  |   Upload to Repo |
+------------------+       +------------------+       +------------------+
|                          |                          |
+--------------------------+--------------------------+
```

Each configuration is tested for:

- Connectivity  
- Latency  
- Stability  
- Handshake success  

Only configs that pass all checks are added.

---

# 🔗 Direct Raw Config URLs

You can copy and paste the following raw configuration URLs directly into your V2Ray client.  
Each link always points to the **latest version** of the corresponding config.

---

## 📡 Quick Copy Table

| ISP / Network | Badge | Raw Link | Copy Button | QR Code |
|--------------|--------|----------|-------------|---------|
| **ALL / LTE** | ![MCI](https://img.shields.io/badge/MCI-Mobile-red) | `https://raw.githubusercontent.com/sohrablou/Config-v2/refs/heads/main/config/ALL.txt#ALL Config` | <a href="https://raw.githubusercontent.com/sohrablou/Config-v2/refs/heads/main/config/ALL.txt#ALL Config"><img src="https://img.shields.io/badge/Copy-ALL-red?style=for-the-badge"></a> | <img src="https://api.qrserver.com/v1/create-qr-code/?size=150x150&data=https://raw.githubusercontent.com/sohrablou/Config-v2/refs/heads/main/config/ALL.txt#ALL Config" width="120"> |
| **MCI / LTE** | ![MCI](https://img.shields.io/badge/MCI-Mobile-blue) | `https://raw.githubusercontent.com/sohrablou/Config-v2/refs/heads/main/config/MCI.txt#MCI Config` | <a href="https://raw.githubusercontent.com/sohrablou/Config-v2/refs/heads/main/config/MCI.txt#MCI Config"><img src="https://img.shields.io/badge/Copy-MCI-blue?style=for-the-badge"></a> | <img src="https://api.qrserver.com/v1/create-qr-code/?size=150x150&data=https://raw.githubusercontent.com/sohrablou/Config-v2/refs/heads/main/config/MCI.txt#MCI Config" width="120"> |
| **IRN / LTE** | ![IRN](https://img.shields.io/badge/IRN-Mobile-yellow) | `https://raw.githubusercontent.com/sohrablou/Config-v2/refs/heads/main/config/IRN.txt#IRANCELL Config` | <a href="https://raw.githubusercontent.com/sohrablou/Config-v2/refs/heads/main/config/IRN.txt#IRANCELL Config"><img src="https://img.shields.io/badge/Copy-IRN-yellow?style=for-the-badge"></a> | <img src="https://api.qrserver.com/v1/create-qr-code/?size=150x150&data=https://raw.githubusercontent.com/sohrablou/Config-v2/refs/heads/main/config/IRN.txt#IRANCELL Config" width="120"> |

---

## 📡 ALL (Mobile / LTE)
```bash
https://raw.githubusercontent.com/sohrablou/Config-v2/refs/heads/main/config/ALL.txt#ALL Config
```

## 📡 MCI (Mobile / LTE)
```bash
https://raw.githubusercontent.com/sohrablou/Config-v2/refs/heads/main/config/MCI.txt#MCI Config
```

## 🛰️ IRN (Mobile / LTE)
```bash
https://raw.githubusercontent.com/sohrablou/Config-v2/refs/heads/main/config/IRN.txt#IRANCELL Config
```

---

## 🖼️ Screenshots & Diagrams

### Importing a config (conceptual diagram)
```bash
+-----------------------+
|   V2RayNG Client      |
+-----------------------+
|  Import Config        |
|        ↓              |
|  Select TXT File      |
|        ↓              |
|  Connection Added ✔️  |
+-----------------------+
```

---

## ❓ FAQ

### **Why is a config not working anymore?**  
Configs may expire or become unstable over time. This is normal for temporary or public servers.

### **How often are configs updated?**  
Whenever new working connections are found and tested.

### **Can I share this repo publicly?**  
Preferably **no**. Public sharing increases server load and reduces config lifespan.

---

## 🛠️ Troubleshooting

### **Config imported but no internet**  
- Try switching between TCP / WS / gRPC modes  
- Restart your client  
- Test another config  

### **High ping or slow speed**  
- This is common with free or temporary servers  
- Try another config  
- Switch network (WiFi ↔ Mobile Data)

---

## 📝 Notes

- This project is for **personal and friendly use only**  
- No guarantees of uptime or long-term stability  
- Configs may stop working at any time  

---

## 🤝 Contributing

Suggestions for improving structure, automation, or documentation are welcome.

---

## ⭐ Support

If this repository helps you, consider giving it a **star** to keep it visible.
