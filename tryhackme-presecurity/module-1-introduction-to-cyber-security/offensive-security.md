# Offensive Security

## Overview

Offensive Security is a cybersecurity practice focused on actively testing systems to find vulnerabilities before malicious attackers do.

Professionals in this field simulate real-world attacks to identify weaknesses in systems, applications, and networks.

Common roles include:

- Penetration Tester
- Red Team Operator
- Ethical Hacker

The goal is to improve security by discovering vulnerabilities before they are exploited by attackers.

---

# Your First Hack (Concept)

In this lab, we simulate attacking a vulnerable banking application called **FakeBank**.

The objective is to discover hidden functionality that normal users should not access.

One common technique used is **directory brute forcing**.

---

# Hidden URLs

Web applications sometimes contain hidden pages that are not linked in the main interface.

Examples:

- admin panels
- backup files
- development endpoints
- hidden login portals

Attackers attempt to discover these pages using automated tools.

---

# Directory Brute Forcing

Directory brute forcing is a technique used to discover hidden directories or pages on a web server.

The attacker uses a wordlist of common page names and tests them against the website.

Example possible pages:
/admin
/login
/dashboard
/backup
/test

# dirb Tool

One tool used in the lab is **dirb**.

`dirb` is a web content scanner used to find hidden directories and files in web servers.

Example usage:
dirb http://example.com

The tool works by:

1. Taking a list of potential directory names
2. Sending requests to the web server
3. Checking which pages exist

If a page exists, the server returns a valid response.

---

# Terminal Usage

Many cybersecurity tools run inside the **terminal / command line**.

A terminal allows users to interact with the operating system using text commands.

Common terminals include:

- Linux Terminal
- Windows Command Prompt
- PowerShell

---

# Key Takeaways

From this room we learn:

- The concept of **Offensive Security**
- How attackers discover **hidden website pages**
- The basics of **directory brute forcing**
- Using tools like **dirb**
- Basic usage of a **terminal**

---

# Disclaimer

This documentation is for educational purposes only.

The techniques discussed should only be used in **legal environments such as labs, CTF platforms, or systems you own or have permission to test**.

---

# Completion Proof

<img width="1310" height="541" alt="image" src="https://github.com/user-attachments/assets/f17d1e6b-6bbf-49ec-8a2c-fc52d67d0e52" />

**note** Gambar di atas menunjukkan progres saya dalam memahami dasar offensive security 
