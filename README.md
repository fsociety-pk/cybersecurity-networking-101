```
   _____ _____________  _____ _____________ ________  
  / ___// ____/ ____/ /:  ____/__  ______/ /_  __/ /
 \___ \/ __/ / /   / / / __/   / /       _/ / / /_/
/___/ / /___/ /___/ /_/ /___  / /      /__/ / / / _ \
/_____/_____/\____/____/_____/ /_/        /_(_)_/ /_/ 
                                                       
    CYBERSECURITY NETWORKING 101
    Networking Fundamentals for Ethical Hackers
    F-Society PK Learning Organization
```

---

## Mission

Master networking fundamentals essential for cybersecurity professionals. Learn packet analysis, protocol exploitation, network reconnaissance, and defensive strategies used by security professionals worldwide.

---

## What's Inside

This repository contains **complete networking fundamentals** for anyone pursuing cybersecurity:

### Core Learning Materials

#### 1. **Evolution of Networking** 
Historical timeline from ARPANET (1960) to 5G/IoT (2020). Understand how the internet evolved and key security-related milestones.

#### 2. **Networking in Cybersecurity**
Why hackers need networking knowledge:
- Packet sniffing and traffic analysis
- Protocol exploitation techniques
- Network reconnaissance (Nmap, port scanning)
- Firewall evasion and bypass strategies

#### 3. **Network Types & Classifications**
Understanding different network scopes:
- **LAN** - Local Area Networks (office, school)
- **WAN** - Wide Area Networks (internet, global)
- **MAN** - Metropolitan Area Networks (city-wide)
- **PAN** - Personal Area Networks (Bluetooth, mobile)

#### 4. **Essential Networking Devices**
How network infrastructure works:
- **Routers** - Forward packets between networks (Layer 3)
- **Switches** - Connect devices on same network (Layer 2)
- **Firewalls** - Filter and block traffic based on rules (Layer 3-7)
- **Modems** - Convert digital/analog signals (Layer 1)
- **Access Points** - Provide wireless connectivity (Layer 2)

#### 5. **IP Addressing Deep Dive**
Master addressing schemes:
- **IPv4** vs **IPv6** formats and structure
- **Public vs Private** IP addresses and RFC 1918 ranges
- **Static vs Dynamic** IP assignments
- **IP Classes** (A, B, C, D, E) and their uses
- **MAC Addresses** vs Logical IPs

#### 6. **Subnetting & CIDR**
Network division and optimization:
- CIDR notation (/8, /16, /24, /32)
- Subnet mask calculations
- Network address calculation
- Host address ranges
- Practical subnetting scenarios

#### 7. **Protocols & Ports**
Critical protocol knowledge:
- **HTTP** (80) - Web traffic
- **HTTPS** (443) - Encrypted web (SSL/TLS)
- **SSH** (22) - Secure shell access
- **FTP** (21) - File transfer
- **DNS** (53) - Domain resolution
- **SMTP** (25) - Email sending
- Port ranges: Well-known (0-1023), Registered (1024-49151), Dynamic (49152-65535)

#### 8. **OSI & TCP/IP Models**
Understanding network layers:
- **OSI Model** (7 layers) - Conceptual framework
  - Layer 7: Application
  - Layer 6: Presentation
  - Layer 5: Session
  - Layer 4: Transport
  - Layer 3: Network
  - Layer 2: Data Link
  - Layer 1: Physical

- **TCP/IP Model** (4 layers) - Practical implementation
  - Application layer (HTTP, DNS, SMTP)
  - Transport layer (TCP, UDP)
  - Internet layer (IP, ICMP)
  - Network Access layer (Ethernet, WiFi)

#### 9. **TCP Connection Management**
How TCP establishes and closes connections:
- **Three-Way Handshake** (SYN, SYN-ACK, ACK)
- **Four-Way Termination** (FIN, ACK, FIN, ACK)
- Connection states and transitions
- TCP vs UDP comparison

#### 10. **Core Network Services**
Essential infrastructure services:
- **DNS** - Domain Name System resolution process
- **ARP** - Address Resolution Protocol (IP to MAC mapping)
- **ICMP** - Internet Control Message Protocol (ping, traceroute)
- Diagnostic tools and techniques

#### 11. **Encryption Fundamentals**
Security through cryptography:
- **Symmetric Encryption** - Single shared key (AES, DES, 3DES) - Fast, bulk data
- **Asymmetric Encryption** - Public/Private key pairs (RSA, ECC) - Secure exchange
- Encryption process: Plaintext → Ciphertext → Plaintext
- Key exchange mechanisms

#### 12. **Privacy & Anonymity Tools**
Protecting communication:
- **VPN** - Encrypted tunnel to VPN server (Medium anonymity)
- **Proxy** - Request forwarding (Low anonymity)
- **Tor** - Multi-hop anonymous network (High anonymity)
- Traffic flow comparison and use cases

#### 13. **Practical Network Analysis Tools**
Real-world tools for professionals:
- **Wireshark** - Packet capture and deep inspection
- **Nmap** - Host discovery and port scanning
- **Burp Suite** - Web proxy and vulnerability testing
- **Cisco Packet Tracer** - Network simulation and design
- Common Nmap commands and Wireshark filters

---

## Repository Structure

```
cybersecurity-networking-101/
├── README.md                          This file
├── writeup.md                         Complete 13-topic networking guide
├── writeup.pdf                        PDF version (for offline study)
│
├── cheatsheets/                       Quick reference materials
│   ├── ports-and-protocols.md        Common ports and services list
│   ├── subnetting-cheatsheet.md      CIDR notation and formulas
│   └── wireshark-filters.md          Capture filter expressions
│
├── labs/                              Hands-on exercises
│   ├── wireshark-lab.md              Packet analysis lab
│   ├── tcp.port-80.png               HTTP traffic example
│   ├── nmap-ping.png                 Network scanning example
│   ├── dns.png                        DNS resolution diagram
│   └── tcp.port-80.png               TCP port examples
│
└── images/                            Network diagrams
    ├── osi-model.png                 7-layer model visual
    ├── tcp-handshake.png             3-way handshake diagram
    ├── tcp-ip-comparison.png         OSI vs TCP/IP
    ├── ip-classes-table.png          IP class breakdown
    ├── encryption-types.png          Symmetric vs Asymmetric
    ├── dns-resolution.png            DNS query flow
    └── types-of-networking.png       Network type classifications
```

---

## How to Use This Repo

### Learning Path
1. **Start Here** → `writeup.md` (read complete guide)
2. **Quick Lookup** → `cheatsheets/` (during CTF or exam prep)
3. **Practice** → `labs/` (hands-on exercises)
4. **Visualize** → `images/` (understand concepts visually)
5. **Offline Study** → `writeup.pdf` (portable version)

### For CTF Competitions
- Keep cheatsheets open while solving
- Use Wireshark lab for packet analysis challenges
- Reference port numbers and protocols instantly

### For Certifications
- Study writeup.md for concepts
- Use cheatsheets for memorization
- Review images for model understanding
- Complete lab exercises before exam

### For Daily Reference
- Bookmark common sections
- Use cheatsheets for quick lookups
- Return to diagrams when needed

---

## Key Topics At A Glance

| Topic | Key Concepts | Tools |
|-------|--------------|-------|
| IP Addressing | IPv4, IPv6, Public/Private, Classes | `ifconfig`, `ip addr` |
| Subnetting | CIDR, Subnet masks, Network ranges | Calculator, tools |
| Protocols | TCP/UDP, HTTP/HTTPS, DNS, SSH | Wireshark |
| OSI Model | 7 layers, Data flow | Diagrams |
| Encryption | Symmetric, Asymmetric, Key exchange | OpenSSL |
| Services | DNS, ARP, ICMP | nslookup, arp, ping |
| Tools | Wireshark, Nmap, tcpdump | Linux/Windows |

---

## Prerequisites

### For Reading Content
- Basic computer networking knowledge
- Understanding of TCP/IP basics
- Familiarity with command line

### For Lab Exercises
- Wireshark installed
- Nmap installed
- Linux or Windows environment
- Network interface access

### Installation Commands
```bash
# Ubuntu/Debian
sudo apt install wireshark nmap tcpdump

# macOS
brew install wireshark nmap tcpdump

# Windows
# Download from official sites or use package manager
```

---

## Skills You'll Gain

After completing this material, you'll understand:

- How networks are structured and organized
- How devices communicate through protocols
- How to analyze network traffic with Wireshark
- How to scan networks with Nmap
- IP addressing and subnetting calculations
- OSI model layer operations
- Encryption and security concepts
- How firewalls and security tools work
- Network troubleshooting techniques
- Offensive and defensive networking strategies

---

## F-Society PK Learning Organization

This repository is maintained by **F-Society PK** - A community dedicated to cybersecurity education:

- CTF write-ups and solutions
- Certification training materials
- Daily security research updates
- Ethical hacking techniques
- Practical lab exercises
- Community challenges

**GitHub Organization**: [fsociety-pk](https://github.com/fsociety-pk)

---

## Quick Commands Reference

```bash
# View IP configuration
ip addr show
ifconfig

# Scan network for hosts
nmap -sn 192.168.1.0/24

# Scan specific ports
nmap -p 80,443 target.com

# Packet capture
tcpdump -i eth0 'tcp port 80'

# DNS lookup
nslookup google.com
dig google.com

# Show ARP table
arp -a

# Test connectivity
ping 8.8.8.8
traceroute 8.8.8.8
```

---

## Learning Resources

### Official Documentation
- [RFC 1918 - Private IP Addressing](https://tools.ietf.org/html/rfc1918)
- [Wireshark User Guide](https://www.wireshark.org/docs/)
- [Nmap Book](https://nmap.org/book/)

### Recommended Topics to Master
1. IP addressing and subnetting (foundation)
2. TCP/IP model (essential)
3. Common protocols and ports (memorize)
4. Wireshark packet analysis (practical skill)
5. Network reconnaissance (offensive skill)

---

## Contributing

Found an issue or want to contribute?

- Report errors in the GitHub Issues
- Submit improvements via Pull Requests
- Share your lab solutions
- Suggest additional topics

---

## Tips for Success

1. **Practice Subnetting** - Use online calculators first, then solve manually
2. **Capture Real Traffic** - Use Wireshark on your own network
3. **Explore Port Scans** - Run Nmap on test environments
4. **Read RFC Documents** - Understand official specifications
5. **Build Labs** - Set up virtual networks for experimentation
6. **Teach Others** - Explain concepts to reinforce learning
7. **Stay Current** - Follow networking security news

---

## Disclaimer

This material is for **educational purposes only**. Always:
- Obtain proper authorization before network testing
- Use these skills ethically and legally
- Follow your organization's security policies
- Respect privacy and data protection laws
- Never attempt unauthorized network access

---

```
[*] Welcome to Cybersecurity Networking 101
[*] Repository: https://github.com/fsociety-pk/cybersecurity-networking-101
[*] Organization: F-Society PK
[*] Last Updated: April 7, 2026
[*] Status: Ready to learn
```

**Happy Learning! Master networking, master cybersecurity.** 🔐
