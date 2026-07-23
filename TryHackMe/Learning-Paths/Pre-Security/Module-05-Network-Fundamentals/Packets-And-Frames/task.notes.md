# Packets & Frames

## Room Information

- **Module:** Module 05 – Network Fundamentals
- **Room:** Packets & Frames
- **Status:** ✅ Complete
- **Difficulty:** Easy

---

# Room Objective

Learn how data is encapsulated into packets and frames, understand the differences between TCP and UDP, explore the TCP Three-Way Handshake, learn the purpose of network ports, and reinforce these concepts through practical labs.

---

# Tasks Completed

## ✅ Task 1 – What are Packets and Frames?

### Topics

- Packets
- Frames
- Encapsulation
- Decapsulation

### Questions

| Question | Answer |
|----------|--------|
| What is data called when it has IP addressing information? | Packet |
| What is data called when it does not have IP addressing information? | Frame |

**Screenshot**

```text
packets-and-frames-task01-what-are-packets-and-frames
```

---

## ✅ Task 2 – TCP/IP (The Three-Way Handshake)

### Topics

- TCP/IP Model
- Encapsulation
- TCP Headers
- Three-Way Handshake

### Questions

| Question | Answer |
|----------|--------|
| What TCP header ensures data integrity? | Checksum |
| Order of the Three-Way Handshake | SYN, SYN/ACK, ACK |

**Screenshot**

```text
packets-and-frames-task02-tcp-ip-three-way-handshake
```

---

## ✅ Task 3 – Practical: TCP Three-Way Handshake

### Objective

Reassemble the TCP handshake in the correct order.

### Flag

```text
THM{TCP_CHATTER}
```

**Lab Screenshot**

```text
packets-and-frames-task03-tcp-three-way-handshake-lab
```

---

## ✅ Task 4 – UDP/IP

### Topics

- User Datagram Protocol
- Stateless Communication
- UDP Headers
- TCP vs UDP

### Questions

| Question | Answer |
|----------|--------|
| What does UDP stand for? | User Datagram Protocol |
| What type of connection is UDP? | Stateless |
| What protocol would you use to transfer a file? | TCP |
| What protocol would you use for a video call? | UDP |

**Screenshot**

```text
packets-and-frames-task04-user-datagram-protocol
```

---

## ✅ Task 5 – Ports 101 (Practical)

### Topics

- Network Ports
- Common Ports
- Standard Services

### Common Ports Learned

| Protocol | Port |
|----------|-----:|
| FTP | 21 |
| SSH | 22 |
| HTTP | 80 |
| HTTPS | 443 |
| SMB | 445 |
| RDP | 3389 |

### Practical

Connected to:

- IP Address: **8.8.8.8**
- Port: **1234**

### Flag

```text
THM{YOU_CONNECTED_TO_A_PORT}
```

**Lab Screenshot**

```text
packets-and-frames-task05-ports-lab
```

---

## Room Completion Screenshot

```text
packets-and-frames-room-complete
```

---

# Skills Developed

- Packets
- Frames
- Encapsulation
- Decapsulation
- TCP/IP Model
- TCP
- UDP
- Three-Way Handshake
- SYN
- SYN/ACK
- ACK
- FIN
- RST
- TCP Headers
- UDP Headers
- Checksums
- Sequence Numbers
- Network Ports
- Common Service Ports
- Network Communication

---

# Key Takeaways

- Packets operate at Layer 3 of the OSI Model.
- Frames operate at Layer 2.
- TCP provides reliable, connection-oriented communication.
- UDP provides faster, connectionless communication.
- TCP establishes connections using the Three-Way Handshake.
- Ports identify specific network services.
- Understanding ports and protocols is essential for network troubleshooting and cybersecurity.

---

# Screenshot Checklist

## Task Screenshots

- packets-and-frames-task01-what-are-packets-and-frames
- packets-and-frames-task02-tcp-ip-three-way-handshake
- packets-and-frames-task04-user-datagram-protocol

## Lab Screenshots

- packets-and-frames-task03-tcp-three-way-handshake-lab
- packets-and-frames-task05-ports-lab

## Room Completion

- packets-and-frames-room-complete