# 🚀 Ubuntu Server Deployment & Monitoring Project

## 📌 Overview
This project demonstrates a Linux server setup with:
- Web hosting using NGINX
- Custom UI deployment
- System monitoring using Netdata
- Server configuration and debugging

---

## 🧱 Architecture

```mermaid
graph TD;
    A[User Browser] --> B[NGINX Web Server - Port 80];
    B --> C[Custom Web UI];
    B --> D[Netdata Monitoring - Port 19999];
    D --> E[System Metrics CPU / RAM / Disk];
```

---

## 🛠️ Tech Stack
- Ubuntu Server
- NGINX
- Netdata
- Linux Shell
- HTML/CSS

---

## 📸 Screenshots

### Web UI
![NGINX UI](screenshots/nginx-ui.png)

### Monitoring Dashboard
![Netdata](screenshots/netdata-dashboard.png)

### Terminal Output
![Terminal](screenshots/terminal-status.png)

---

## ⚙️ Setup Summary

1. Install NGINX
2. Create web UI
3. Install Netdata
4. Configure binding to 0.0.0.0
5. Open ports 80 & 19999
6. Debug service issues

---

## 🧠 What I Learned
- Linux server administration
- Web hosting with NGINX
- Monitoring systems
- Network ports and bindings
- Debugging service failures

---

## 👤 Author
Aishwarya
