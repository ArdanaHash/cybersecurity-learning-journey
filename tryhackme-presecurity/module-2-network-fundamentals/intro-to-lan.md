# Introduction to LAN

## Overview

A Local Area Network (LAN) is a network that connects devices within a limited geographic area, such as a home, office, or school.

LANs allow devices to communicate with each other and share resources like files, printers, and internet connections.

Devices commonly found in a LAN include:

- computers
- laptops
- printers
- switches
- routers

---

# Network Topologies

A network topology describes the layout or structure of how devices are connected in a network.

Some common LAN topologies include:

## Star Topology

In a star topology, all devices connect to a central device such as a switch or hub.

Advantages:

- easy to manage
- easy to add new devices

Disadvantages:

- if the central device fails, the entire network may stop working.

---

## Bus Topology

In a bus topology, all devices share a single communication line.

Advantages:

- simple design
- requires less cable

Disadvantages:

- network performance can decrease if many devices are connected.

---

## Ring Topology

In a ring topology, devices are connected in a circular structure.

Data travels from one device to another until it reaches its destination.

If one connection breaks, communication in the network may be disrupted.

---

# Subnetting (Basic Concept)

Subnetting is a technique used to divide a larger network into smaller networks.

Benefits of subnetting include:

- improved network organization
- better performance
- improved security

Subnetting helps manage IP addresses efficiently within a network.

---

# ARP (Address Resolution Protocol)

ARP is used to map an **IP address** to a **MAC address** within a local network.

When a device wants to communicate with another device, it first needs to know the MAC address associated with the destination IP address.

ARP helps the device discover this information.

---

# DHCP (Dynamic Host Configuration Protocol)

DHCP is a protocol used to automatically assign IP addresses to devices in a network.

Without DHCP, network administrators would need to configure IP addresses manually.

When a device joins a network, the DHCP server can automatically provide:

- an IP address
- subnet mask
- default gateway
- DNS server information

---

# Key Takeaways

- LAN connects devices within a small geographic area.
- Network topology describes how devices are connected.
- Subnetting helps organize and manage networks.
- ARP resolves IP addresses to MAC addresses.
- DHCP automatically assigns IP addresses to devices in a network.

---

# Disclaimer

This repository contains my personal notes from TryHackMe learning paths.

No flags, walkthroughs, or copyrighted course materials are included.

This documentation is created for educational purposes as part of a cybersecurity learning journey.

All techniques discussed should only be used in authorized environments such as labs, training platforms, or systems you own.

---

# Completion Proof

<img width="1862" height="307" alt="image" src="https://github.com/user-attachments/assets/16260c03-5c2c-4774-ba24-ea8d38457449" />

**note** The image above shows my progress in understanding the basics of LAN.
