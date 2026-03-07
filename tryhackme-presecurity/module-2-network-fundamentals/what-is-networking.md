# What is Networking

## Overview

Networking refers to connecting multiple devices so they can communicate and exchange data. These devices may include computers, servers, smartphones, routers, and other network-enabled hardware.

Networking enables devices to share resources such as internet access, files, and services.

---

# What is the Internet

The Internet is a global network that connects many smaller networks around the world. It allows devices to communicate using standard networking protocols.

When a device connects to the internet, it must have a unique identifier so other devices know where to send data.

This identifier is called an **IP Address**.

---

# Identifying Devices on a Network

Devices in a network must be uniquely identifiable. Two main identifiers are commonly used:

- IP Address
- MAC Address

These identifiers help ensure that data reaches the correct destination.

---

# IP Address

An **IP Address (Internet Protocol Address)** is a numerical label assigned to a device connected to a network.

Example:

192.168.1.1

In IPv4 format, an IP address consists of **four numbers separated by dots**. Each number ranges from **0 to 255**.

Example structure:

192 . 168 . 1 . 1

Each section is called an **octet**.

The IP address allows devices to locate and communicate with each other within a network.

---

# Public vs Private IP Addresses

IP addresses are categorized into two main types.

## Private IP Address

Private IP addresses are used inside local networks such as home networks or company networks.

Common private IP ranges include:

192.168.x.x  
10.x.x.x  
172.16.x.x – 172.31.x.x  

Devices using private IP addresses communicate within the local network.

---

## Public IP Address

A public IP address is assigned by an Internet Service Provider (ISP) and is used for communication across the internet.

Public IP addresses allow devices and servers to be reachable from the internet.

---

# IPv4 and IPv6

## IPv4

IPv4 uses a 32-bit address system and is the most widely used version of IP.

Example:

86.157.52.21

IPv4 can support approximately **4.3 billion addresses**.

Due to the growth of the internet, IPv4 addresses are becoming limited.

---

## IPv6

IPv6 was introduced to solve the address shortage problem.

Example IPv6 address:

2a00:22c4:531:c500:425f:cecc:c36b:f64d

IPv6 uses a much larger address space and supports significantly more devices.

---

# MAC Address

A **MAC Address (Media Access Control Address)** is a unique hardware identifier assigned to a network interface.

Example:

34:c3:f0:85:ac:2d

MAC addresses are typically represented as six pairs of hexadecimal numbers separated by colons.

Example format:

XX:XX:XX:XX:XX:XX

The first part usually identifies the manufacturer of the network interface, while the remaining part uniquely identifies the device.

---

# IP Address vs MAC Address

Both identifiers are important but serve different purposes.

| IP Address | MAC Address |
|-------------|-------------|
| Logical network identifier | Hardware identifier |
| Can change depending on network | Usually fixed to hardware |
| Used for routing data across networks | Used for communication within local networks |

---

# Ping and ICMP

The **ping** command is used to test connectivity between devices on a network.

Example command:

ping google.com

Ping uses the **ICMP (Internet Control Message Protocol)** to send requests and measure response time.

If the destination responds, it indicates that the network connection is working.

---

# Key Takeaways

- Networking allows devices to communicate and share resources.
- The Internet connects networks globally.
- Devices are identified using **IP addresses** and **MAC addresses**.
- IPv4 is the traditional addressing system, while IPv6 supports a much larger address space.
- Tools such as **ping** help test network connectivity.

---

# Disclaimer

This repository contains my personal notes from TryHackMe learning paths.

No flags, walkthroughs, or copyrighted course materials are included.

This documentation is created for educational purposes as part of a cybersecurity learning journey.

All techniques discussed should only be used in authorized environments such as labs, training platforms, or systems you own.

---

# Completion Proof

<img width="911" height="922" alt="image" src="https://github.com/user-attachments/assets/7bef13ed-d8bc-4d43-b7c8-b8c6dea0bfb2" />


**note** The image above shows my progress in understanding the basics of networking.
