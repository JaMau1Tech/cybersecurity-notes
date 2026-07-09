# Investigation 01 - Website Traffic Analysis

## Objective

Capture and analyze network traffic generated while visiting websites using Wireshark. Identify the stages involved in establishing a secure HTTPS connection.

---

# Notebook Notes

• Wireshark captures live network packets.

• A network interface sends and receives network traffic.

• Packets are individual units of network communication.

• Display filters isolate specific protocols.

• DNS resolves domain names into IP addresses.

• Standard Query = Client requests an IP address.

• Standard Query Response = DNS server returns the IP address.

• TCP establishes reliable communication.

• TCP Three-Way Handshake:
  - SYN
  - SYN, ACK
  - ACK

• HTTPS encrypts traffic using TLS.

• Client Hello starts the TLS handshake.

• Server Hello accepts the secure connection.

• Port 443 is the default HTTPS port.

• After the TLS handshake, application data is encrypted.

---

# Lab Steps

## Task 1 – Select the Network Interface

- Open Wireshark.
- Identify the active network interface.
- Select the interface displaying live traffic.
- Prepare for packet capture.

---

## Task 2 – Capture Live Traffic

Start capturing packets.

Visit the following websites:

- https://tryhackme.com
- https://github.com
- https://google.com

Allow traffic to generate for several seconds.

Stop the packet capture.

Observe:

- Total packets captured
- Different protocol colors
- Live packet activity

---

## Task 3 – Analyze DNS Traffic

Apply the display filter:

```text
dns
```

Observe:

- Standard Query
- Standard Query Response
- Domain names
- Returned IP addresses

Record:

- DNS server
- Queried domains
- Number of DNS packets displayed

---

## Task 4 – Analyze TCP Connections

Apply the display filter:

```text
tcp
```

Locate a TCP Three-Way Handshake.

Identify:

- SYN
- SYN, ACK
- ACK

Observe how the TCP connection is established before data transfer.

---

## Task 5 – Analyze TLS Handshake

Apply the display filter:

```text
tls
```

Locate:

- Client Hello
- Server Hello
- Change Cipher Spec
- Application Data

Observe:

- Destination IP
- Port 443
- TLS Version

Verify that application data is encrypted.

---

## Task 6 – Investigation Summary

Communication sequence:

1. User enters website URL.
2. DNS resolves the domain name.
3. TCP establishes a connection.
4. TLS negotiates encryption.
5. HTTPS transfers encrypted application data.

---

# Screenshot Checklist

```text
wireshark-home-screen
```

```text
wireshark-capture-started
```

```text
wireshark-capture-complete
```

```text
wireshark-dns-filter-results
```

```text
wireshark-tcp-three-way-handshake
```

```text
wireshark-tls-client-hello
```

---

# Lessons Learned

- Learned how to capture live network traffic using Wireshark.
- Identified the active network interface for packet capture.
- Used display filters to isolate DNS, TCP, and TLS traffic.
- Observed DNS resolving domain names into IP addresses.
- Identified the TCP Three-Way Handshake used to establish reliable connections.
- Analyzed the TLS handshake used to secure HTTPS communication.
- Confirmed that HTTPS encrypts application data after the TLS handshake.
- Developed foundational packet analysis skills applicable to network troubleshooting and security investigations.