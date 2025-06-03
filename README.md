# ⚔️ Capture the Flag: Offensive Security in Action

## 🔍 Cybersecurity Lab Challenge — Network Scanning & Exploitation

**🧪 Project Title:** Vulnerability Assessment & Exploitation of a Simulated Target  
**📘 Organized by:** DevTown

---

## 🎯 Project Goal

This hands-on project simulates a real-world penetration testing scenario. The objective is to identify and exploit vulnerabilities in a deliberately insecure virtual machine using standard tools and techniques.

---

## 🛠️ Tools & Techniques Used

- **Netdiscover** – For network reconnaissance and IP discovery  
- **Nmap** – Port scanning, service detection, and OS fingerprinting  
- **Metasploit Framework** – Exploitation of known vulnerabilities  
- **Linux Command-Line** – For system navigation and information gathering  
- **John the Ripper / Hashcat** – For cracking encrypted passwords

---

## 🚀 Implementation Steps

### 1. Initial Reconnaissance  
The target IP was discovered using `netdiscover`, allowing identification of the machine on the local network.

### 2. Port & Service Scanning  
An in-depth **Nmap** scan was performed to enumerate open ports and detect services and OS details.

### 3. Vulnerability Detection  
A vulnerable version of the FTP service (**ProFTPD 1.3.3c**) was identified, known to be exploitable.

### 4. Exploitation  
Using the **Metasploit Framework**, an exploit was launched against the FTP service, granting shell access to the system.

### 5. Post-Exploitation  
Once inside the system, files like `/etc/passwd` were examined to gather user information. Cracking tools such as **John the Ripper** and **Hashcat** were discussed for further credential attacks.

---

## 📂 Proof of Concept

All supporting files, terminal outputs, and notes are included in the `/PoC` directory of this repository.

---

## 📌 Key Takeaways

- Gained practical experience in each phase of a penetration test
- Learned to identify and exploit vulnerabilities in real services
- Improved familiarity with cybersecurity tools and techniques
- Practiced ethical hacking in a controlled lab environment

---

> ⚠️ **Disclaimer:** This project was conducted in a legal, educational environment. Never attempt unauthorized testing on live systems.
