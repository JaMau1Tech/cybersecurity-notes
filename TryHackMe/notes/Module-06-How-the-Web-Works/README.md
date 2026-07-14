# Module 06 – How The Web Works

## Overview

This module introduces the core technologies that make the World Wide Web function. It covers how domain names are resolved, how browsers communicate with web servers, how websites are built, and how all of these technologies work together during a complete web request.

These concepts form an essential foundation for web application security, penetration testing, network analysis, API testing, and security troubleshooting.

---

## Module Objectives

- Understand the purpose and operation of DNS
- Learn how HTTP and HTTPS enable web communication
- Understand URL structure
- Interpret HTTP requests and responses
- Identify common HTTP methods and status codes
- Understand HTTP headers and cookies
- Learn how websites are structured and delivered
- Understand the complete web request lifecycle
- Build a strong foundation for web application security

---

## Rooms

| Status | Room | Description |
|---|---|---|
| ✅ | DNS in Detail | Learn how DNS translates human-readable domain names into IP addresses. |
| ✅ | HTTP in Detail | Learn how browsers request content from web servers using HTTP and HTTPS. |
| ⬜ | How Websites Work | Learn how websites are created using client-side and server-side technologies. |
| ⬜ | Putting it all together | Combine DNS, HTTP, browsers, servers, and website technologies into the complete web request lifecycle. |

---

## Skills Learned

### DNS Fundamentals

- Domain Name System
- Domain hierarchy
- Root domains
- Top-Level Domains
- Generic Top-Level Domains
- Country Code Top-Level Domains
- Second-Level Domains
- Subdomains
- DNS resolution
- DNS caching
- Time To Live

### DNS Record Types

- A
- AAAA
- CNAME
- MX
- TXT

### HTTP and HTTPS Fundamentals

- HyperText Transfer Protocol
- HyperText Transfer Protocol Secure
- TLS encryption
- Client-server communication
- HTTP requests
- HTTP responses
- HTTP protocol versions
- URL structure
- Query parameters
- Body parameters

### HTTP Methods

- GET
- POST
- PUT
- DELETE
- CRUD operations

### HTTP Status Codes

- 1xx informational responses
- 2xx successful responses
- 3xx redirection responses
- 4xx client errors
- 5xx server errors
- 200 OK
- 201 Created
- 301 Moved Permanently
- 302 Found
- 400 Bad Request
- 401 Unauthorized
- 403 Forbidden
- 404 Not Found
- 405 Method Not Allowed
- 500 Internal Server Error
- 503 Service Unavailable

### HTTP Headers

#### Request Headers

- Host
- User-Agent
- Content-Length
- Accept-Encoding
- Cookie

#### Response Headers

- Set-Cookie
- Cache-Control
- Content-Type
- Content-Encoding

### Cookies and Sessions

- HTTP statelessness
- Cookie storage
- Session tracking
- Authentication cookies
- Browser cookie handling
- Set-Cookie responses
- Cookie request headers

### Practical Skills

- Querying DNS records
- Identifying DNS record types
- Understanding DNS responses
- Tracing the DNS resolution process
- Using DNS lookup tools
- Building GET requests
- Building POST requests
- Building PUT requests
- Building DELETE requests
- Configuring URI parameters
- Configuring request body parameters
- Interpreting HTTP responses
- Analyzing HTTP headers
- Understanding browser-server communication

### Cybersecurity Relevance

- DNS enumeration
- Web reconnaissance
- Network troubleshooting
- Email security analysis
- Phishing investigations
- Threat hunting
- Web application penetration testing
- API testing
- Authentication testing
- Session analysis
- Burp Suite request inspection
- HTTP traffic analysis

---

## Completed Rooms

### ✅ DNS in Detail

#### Overview

This room introduced the Domain Name System and explained how domain names are translated into IP addresses. It covered domain hierarchy, common DNS record types, the DNS lookup process, caching, and practical DNS queries.

#### Topics Covered

- What DNS is
- Domain hierarchy
- Top-Level Domains
- Second-Level Domains
- Subdomains
- A records
- AAAA records
- CNAME records
- MX records
- TXT records
- Recursive DNS servers
- Root DNS servers
- TLD servers
- Authoritative DNS servers
- DNS caching
- Time To Live
- Practical DNS queries

#### Practical Experience

- Queried the CNAME record for `shop.website.thm`
- Retrieved the TXT record for `website.thm`
- Identified the MX priority value
- Retrieved the A record for `www.website.thm`

#### Documentation

```text
DNS-in-Detail/task-notes.md
```

#### Screenshot Count

```text
6 screenshots
```

---

### ✅ HTTP in Detail

#### Overview

This room introduced HTTP and HTTPS and explained how browsers communicate with web servers. It covered URL components, HTTP requests and responses, methods, status codes, headers, cookies, and practical request creation.

#### Topics Covered

- HTTP
- HTTPS
- TLS encryption
- URL structure
- Schemes
- Hosts
- Ports
- Paths
- Query strings
- Fragments
- HTTP requests
- HTTP responses
- HTTP methods
- HTTP status codes
- Request headers
- Response headers
- Cookies
- Sessions
- Query parameters
- Body parameters

#### Practical Experience

- Made a GET request to `/room`
- Made a GET request to `/blog` with `id=1`
- Made a DELETE request to `/user/1`
- Made a PUT request to `/user/2`
- Submitted `username=admin` in the PUT request body
- Made a POST request to `/login`
- Submitted `username=thm`
- Submitted `password=letmein`

#### Documentation

```text
HTTP-in-Detail/task-notes.md
```

#### Screenshot Count

```text
8 screenshots
```

---

## Screenshots

All screenshots for this module are stored in the shared module images directory:

```text
images/
```

The complete screenshot index is documented in:

```text
images/README.md
```

### Current Screenshot Summary

| Room | Screenshot Count |
|---|---:|
| DNS in Detail | 6 |
| HTTP in Detail | 8 |
| How Websites Work | 0 |
| Putting it all together | 0 |
| **Total** | **14** |

---

## Repository Structure

```text
Module-06-How-The-Web-Works/
│
├── README.md
│
├── images/
│   ├── README.md
│   ├── dns-in-detail-task01-what-is-dns.png
│   ├── dns-in-detail-task02-domain-hierarchy.png
│   ├── dns-in-detail-task03-record-types.png
│   ├── dns-in-detail-task04-dns-request-process.png
│   ├── dns-in-detail-task05-dns-practical.png
│   ├── dns-in-detail-room-complete.png
│   ├── http-in-detail-task01-what-is-https.png
│   ├── http-in-detail-task02-requests-and-responses.png
│   ├── http-in-detail-task03-http-methods.png
│   ├── http-in-detail-task04-http-status-codes.png
│   ├── http-in-detail-task05-headers.png
│   ├── http-in-detail-task06-cookies.png
│   ├── http-in-detail-task07-making-requests.png
│   └── http-in-detail-room-complete.png
│
├── DNS-in-Detail/
│   └── task-notes.md
│
├── HTTP-in-Detail/
│   └── task-notes.md
│
├── How-Websites-Work/
│   └── task-notes.md
│
└── Putting-it-all-Together/
    └── task-notes.md
```

---

## Module Progress

| Room | Status |
|---|---|
| DNS in Detail | ✅ Completed |
| HTTP in Detail | ✅ Completed |
| How Websites Work | ⬜ Not Started |
| Putting it all together | ⬜ Not Started |

**Rooms Completed:** 2 / 4

**Module Completion:** 50%

```text
██████████░░░░░░░░░░ 50%
```

---

## Next Room

### ➡️ How Websites Work

The next room introduces how websites are created and delivered.

Expected topics include:

- HTML
- CSS
- JavaScript
- Front-end technologies
- Back-end technologies
- Web servers
- Databases
- Website security fundamentals

This room will build on the DNS and HTTP knowledge developed in the first two rooms.

---

## Module Status

🚧 **In Progress**

Two of four rooms have been completed.

```text
Completed: 2
Remaining: 2
```