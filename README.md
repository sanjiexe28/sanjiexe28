# Hey, moi c'est Sanji 👋

Passionné d'infra, de sécu, de dev et de tout ce qui clignote dans un rack.  
Je construis des trucs, je les casse, je les rebuild mieux.

---

## 🧰 Ce sur quoi je bosse

- 🏠 **Home lab** — VLANs, Proxmox, Pi-hole, monitoring réseau, dashboards custom
- 🔒 **Dev** — site web, scripts
- 🛠️ **Sysadmin** — Linux, Nginx, Tailscale, Netdata, tout ce qui tourne sur du métal

---

## 🖥️ Stack & outils

![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Raspberry Pi](https://img.shields.io/badge/Raspberry%20Pi-A22846?style=flat-square&logo=raspberrypi&logoColor=white)
![Proxmox](https://img.shields.io/badge/Proxmox-E57000?style=flat-square&logo=proxmox&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Tailscale](https://img.shields.io/badge/Tailscale-242424?style=flat-square&logo=tailscale&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

## 🗂️ Infra home lab (aperçu)

```
┌─────────────────────────────────────┐
│  FW01 — Netgear FVS338              │
│  SW01 — HP ProCurve 2910al-24G      │
│  SW02 — TP-Link Omada ES205G        │
│                                     │
│  SRV-RAS01 — Raspberry Pi 4         │
│    Pi-hole · Netdata · Nginx        │
│    Tailscale · ttyd                 │
│                                     │
│  SRV-SUP01 — Dell Latitude 5290     │
│    Proxmox VE                       │
└─────────────────────────────────────┘
VLANs : transit · devices · servers · supervision
```

> *"Si c'est pas dans un fichier de conf, ça existe pas."*
