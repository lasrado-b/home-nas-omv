# Home NAS Project – OpenMediaVault on Lenovo Y580

A self-hosted Network Attached Storage (NAS) built from a repurposed Lenovo laptop to practice real-world IT skills including system administration, networking, and security hardening.

---

## Overview

- **Hardware**: Lenovo Y580 (Intel i7, 8GB RAM, 1TB HDD)
- **NAS OS**: OpenMediaVault 7 (Debian-based)
- **Storage**: 1TB EXT4 filesystem shared via SMB
- **Access**: Static IP, Web GUI, mapped network drive, SSH
- **Use Case**: File storage, system monitoring, home lab experience

---

## Features Implemented

- ✅ OpenMediaVault installed on USB to free full 1TB disk for storage
- ✅ SMB/CIFS file sharing to Windows and Linux clients
- ✅ SMART monitoring with weekly short and monthly long self-tests
- ✅ Static IP setup for persistent network access
- ✅ Web interface customized with monitoring widgets
- ✅ Lid-close behavior changed to keep NAS running
- ✅ Drive mapped on Windows laptop as a persistent network drive
- ✅ SSH access enabled for remote administration

---

## Security Measures

- Guest access used initially, with plans to migrate to user-based access
- SSH limited to local network (disabled externally)
- `systemd-logind` reconfigured to prevent suspend on lid close
- SMART monitoring configured with temperature and failure alerts

---

## Future Plans

- Add user-based access with folder-specific permissions
- Set up remote access securely using Tailscale or WireGuard VPN
- Enable email alerts for system events and SMART failures
- Explore Docker-based apps (e.g., Plex, Nextcloud, Heimdall)
- Create rsync-based or Duplicati backup jobs to external drive
- Add disk health monitoring plugins or SNMP for lab dashboard

---

## Why I Built This

I'm transitioning into the IT and cybersecurity field and built this NAS to:

- Sharpen hands-on sysadmin skills
- Understand real-world LAN services and network file sharing
- Demonstrate initiative beyond certifications (CompTIA Network+, Google IT Support & Cybersecurity)

---

## 📁 Repo Structure
/
├── README.md
├── docs/
│ ├── screenshots
│ └── config-samples.md

---

## 🔗 Related Skills

- Linux CLI & configuration
- Network services (SMB, SSH, DHCP, DNS)
- Disk monitoring (SMART, logs, usage alerts)
- User management and permissions
- IT troubleshooting and home lab deployment

---

## ✅ Built and Maintained by

**Bosco Lasrado**  
[LinkedIn](https://www.linkedin.com/in/bosco-lasrado/)
