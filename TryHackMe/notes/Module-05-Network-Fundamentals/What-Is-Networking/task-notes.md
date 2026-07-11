# What is Networking?

**Platform:** TryHackMe  
**Module:** Module 05 – Network Fundamentals  
**Room:** What is Networking?  
**Difficulty:** Easy  
**Status:** ✅ Completed

---

# Objective

Learn the fundamental concepts of computer networking, including how networks communicate, how devices are identified, and how basic network troubleshooting works using Ping (ICMP).

---

# Skills Learned

- Understanding computer networks
- Understanding the Internet
- Identifying devices on a network
- IP addressing fundamentals
- MAC addressing fundamentals
- Public vs. Private IP addresses
- IPv4 vs. IPv6
- MAC address spoofing
- Network troubleshooting with Ping
- ICMP fundamentals

---

# Tasks Completed

## Task 1 – What is Networking?

### Concepts

- Networks connect devices together.
- Networks allow communication and resource sharing.
- Networking is the foundation of modern computing.

---

## Task 2 – What is the Internet?

### Concepts

- The Internet is a global network of interconnected networks.
- Public and private networks work together to enable worldwide communication.

---

## Task 3 – Identifying Devices on a Network

### Topics Covered

- Internet Protocol (IP)
- Public IP Addresses
- Private IP Addresses
- IPv4
- IPv6
- Media Access Control (MAC)
- MAC Address Spoofing

### Questions

| Question | Answer |
|----------|--------|
| What does IP stand for? | Internet Protocol |
| What is each section of an IP address called? | Octet |
| How many sections does IPv4 have? | 4 |
| What does MAC stand for? | Media Access Control |

### Lab

Completed the MAC spoofing lab by changing Bob's MAC address to match Alice's, demonstrating how MAC spoofing can bypass weak access controls.

---

## Task 4 – Ping (ICMP)

### Topics Covered

- Internet Control Message Protocol (ICMP)
- Echo Request
- Echo Reply
- Network latency
- Connectivity testing

### Questions

| Question | Answer |
|----------|--------|
| What protocol does Ping use? | ICMP |
| Syntax to ping 10.10.10.10 | `ping 10.10.10.10` |

### Lab

Used the deployable environment to ping **8.8.8.8**, confirming connectivity and retrieving the challenge flag.

---

## Task 5 – Continue Your Learning

Reviewed the recommendation to continue with the **Intro to LAN** room to build on the networking concepts introduced in this room.

---

# Key Takeaways

- Networks enable communication between devices.
- The Internet is the largest public network.
- IP addresses are logical identifiers.
- MAC addresses are physical hardware identifiers.
- IPv6 solves IPv4 address exhaustion.
- MAC spoofing demonstrates why MAC addresses alone should not be trusted.
- Ping uses ICMP to verify connectivity and measure response time.

---

# Labs Completed

## MAC Address Spoofing

**Objective**

Demonstrate how changing a MAC address can allow a device to impersonate another on a network.

**Outcome**

Successfully spoofed Bob's MAC address to match Alice's and gained network access.

---

## Ping (ICMP)

**Objective**

Use Ping to verify connectivity to Google's public DNS server.

**Outcome**

Successfully pinged **8.8.8.8** and retrieved the challenge flag.

---

# Screenshots

- networking-task01-room-introduction
- networking-task02-network-types
- networking-task03-identifying-devices-on-a-network
- networking-task03-mac-address-spoofing-lab
- networking-task04-ping-icmp-overview
- networking-task04-ping-icmp-lab
- networking-room-complete

---

# Lessons Learned

- Networking concepts form the foundation of cybersecurity.
- IP and MAC addresses serve different identification purposes.
- Public and private IP addresses have distinct roles.
- MAC spoofing highlights weaknesses in relying solely on hardware addresses for authentication.
- Ping is an essential diagnostic tool for verifying connectivity and troubleshooting network issues.

---

# Next Steps

Continue with:

- Intro to LAN

to expand understanding of Local Area Networks, switching, routing, and network communication.