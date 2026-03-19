# 🔐 Principles of Security

**Path:** Jr Penetration Tester
**Platform:** TryHackMe

This document summarizes the key concepts I learned while completing the **Principles of Security** module.
The module focuses on the foundational principles used to protect systems, data, and infrastructure in cybersecurity.

---

# 📘 Module Overview

This module introduces the core principles of information security, including how data is protected, how access is controlled, and how organizations defend systems using structured security models and layered defenses.

Main areas covered:

* Defence in Depth
* CIA Triad (Confidentiality, Integrity, Availability)
* Access control and privilege management
* Security models (Bell-LaPadula & Biba)
* Threat modeling and incident response

---

# 🛡️ Defence in Depth

**Key concepts learned:**

* Security should be implemented in **multiple layers**, not a single control.
* If one layer fails, other layers continue to provide protection.
* This approach increases overall resilience of systems and data.

Examples of layers:

* Network security
* Access control
* Monitoring and detection
* Encryption

---

# 🔺 The CIA Triad

**Key concepts learned:**

The CIA Triad is a fundamental model used to guide security policies.

**Confidentiality**

* Ensures data is only accessible to authorized users.
* Implemented using authentication and access control.

**Integrity**

* Ensures data remains accurate and unchanged unless authorized.
* Protected using mechanisms like hashing and validation.

**Availability**

* Ensures systems and data are accessible when needed.
* Achieved through redundancy and reliable infrastructure.

These three elements must work together to maintain strong security.

---

# 🔑 Principle of Least Privilege

**Key concepts learned:**

* Users should only have **minimum access required** to perform their tasks.
* Reduces risk of misuse or damage if an account is compromised.

Access control concepts:

* **PIM (Privileged Identity Management)**

  * Manages user identities and roles.

* **PAM (Privileged Access Management)**

  * Controls and monitors privileged access.

This principle helps reduce the attack surface and improve system security.

---

# 🏗️ Security Models

**Key concepts learned:**

Security models help enforce rules for protecting data based on the CIA Triad.

**Bell-LaPadula Model (Confidentiality)**

* Focuses on preventing data leaks.
* Rules:

  * No Read Up
  * No Write Down

**Biba Model (Integrity)**

* Focuses on maintaining data integrity.
* Rules:

  * No Read Down
  * No Write Up

These models use hierarchical levels to control access to information.

---

# 🎯 Threat Modeling & Incident Response

**Key concepts learned:**

* Threat modeling is used to identify, analyze, and mitigate potential security risks.
* Helps organizations understand where vulnerabilities may exist.

A common approach is **STRIDE**, which includes:

* Spoofing
* Tampering
* Repudiation
* Information Disclosure
* Denial of Service
* Elevation of Privilege

---

### Incident Response Process

When a security incident occurs, a structured response is required:

1. **Preparation** – Ensure plans and resources are ready
2. **Identification** – Detect and confirm the incident
3. **Containment** – Limit the impact of the attack
4. **Eradication** – Remove the root cause
5. **Recovery** – Restore systems to normal operation
6. **Lessons Learned** – Improve future security measures

---

# 📌 Key Takeaways

* Security should be implemented in **layers (Defence in Depth)**.
* The **CIA Triad** is the foundation of information security.
* Limiting access through **Least Privilege** reduces risk significantly.
* Security models enforce rules for protecting data confidentiality and integrity.
* Threat modeling helps identify potential risks before they are exploited.
* Incident response ensures organizations can react effectively to security breaches.

---                   

# ⚠️ Disclaimer

This repository contains **personal learning summaries** from cybersecurity training.

No challenge answers, flags, or copyrighted course materials are included.

---
