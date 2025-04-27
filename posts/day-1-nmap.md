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
```

---

## 🧠 Key Learnings from Today

- The difference between **TCP Connect** scan (`-sT`) and **TCP SYN** scan (`-sS`).
- How to perform **stealth scanning** to avoid detection by firewalls or IDS systems.
- How **OS fingerprinting** tries to guess the device's operating system based on TCP/IP stack responses.
- The importance of **scanning in cybersecurity assessments** — both offense (pentesting) and defense (hardening).

---

## 🚀 Why It Matters

Understanding how to effectively map a network is crucial in both cybersecurity attack simulations and real-world defense.  
Mastering tools like Nmap helps me build a strong technical foundation for penetration testing, red teaming, and incident response.

---

## 🎯 Goal Moving Forward

- Continue "One Day, One Tool" daily.
- Document every tool explored in this blog.
- Practice using the tools in both **safe labs** and **CTF (Capture The Flag)** environments.

---

**Challenge Motto:**  
> *"One tool at a time. One step closer to mastery."*

Stay tuned for tomorrow’s post where I’ll explore another powerful cybersecurity tool!

---

