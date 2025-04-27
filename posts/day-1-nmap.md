# One Day, One Tool: Day 1 - Nmap
Date: 2025-04-27
> Exploring one cybersecurity tool each day to sharpen my skills and build practical experience.

---

Today I started my "One Day, One Tool" challenge, where I pick one cybersecurity tool daily and dive deep into it — understanding its usage, features, and real-world applications.

---

## 🛠️ Today's Tool: Nmap

**What is Nmap?**

Nmap ("Network Mapper") is a free and open-source utility for network discovery and security auditing. It’s widely used by cybersecurity professionals for scanning networks and identifying devices, open ports, running services, and operating systems.

---

## 🔥 Commands I Practiced Today

```bash
# Basic ping scan across the network
nmap -sn 192.168.0.0/24

# TCP SYN scan (fast and stealthy)
nmap -sS 192.168.1.0/24

# Service version detection
nmap -sV scanme.nmap.org

# OS detection
nmap -O 192.168.1.1
