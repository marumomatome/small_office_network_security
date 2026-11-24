# Small Office Network Security

## Project Overview

This project involves designing, implementing and securing a small simulated office network using Cisco Packet Tracer.

The simulated organisation consists of three departments:

- Administration
- Finance
- IT Support

The network connects three employee computers, a switch, a router and a server.

The main objective is to understand how devices communicate within a Local Area Network, configure network addressing, analyse traffic flow, implement basic security measures.

## Project Objectives

- Design a small office network topology.
- Configure IPv4 addresses and subnet masks.
- Configure a router and switch.
- Configure a server.
- Implement DNS and HTTP services.
- Test communication between network devices.
- Implement basic security measures.

## Technologies and Tools

- Cisco PacketTracer
- Ethernet
- HTTP
- TCP/IP
- DNS
- Cisco IOS CLI
- ICMP
- SSH

## Network Architecture

The simulated network contains:

- Router x1
- Switch x1
- PCs x3
- Server x1

## IP Addressing Scheme

The network uses the private IPv4 address range `192.168.10.0/24`.

| Device | IP Address | Subnet Mask |
|---|---|---|
| Router | 192.168.10.1 | 255.255.255.0 |
| Switch | 192.168.10.2 | 255.255.255.0 |
| Server | 192.168.10.10 | 255.255.255.0 |
| Admin PC | 192.168.10.11 | 255.255.255.0 |
| Finance PC | 192.168.10.12 | 255.255.255.0 |
| IT PC | 192.168.10.13 | 255.255.255.0 |

**Default Gateway:** 192.168.10.1

**DNS Server:** 192.168.10.10

## Network Services

### DNS Configuration

A DNS service is configured on the central server to translate the internal domain name into an IP address.

Domain: `www.myoffice.local`

IP Address: `192.168.10.10`

### HTTP Configuration

An internal company website is hosted on the server.

Employees can access the website using:

`http://www.myoffice.local`

## Networking Protocols

| Protocol |
|---|
| IPv4 |
| TCP |
| UDP |
| DNS |
| HTTP |
| ICMP |
| ARP |
| Ethernet |

## Security Measures

The project has the following basic security measures:

1. Router administrator authentication.
2. SSH for secure remote device administration.
3. Switch port security using sticky MAC addresses.
4. Shutdown of unused switch ports.
5. Strong administrator password policies.
6. Role-based access recommendations for departmental data.

## Testing and Verification

The following tests are used to evaluate network connectivity and functionality:

| Test | Purpose |
|---|---|
| PC-to-PC ping | Test communication between workstations |
| PC-to-server ping | Verify server connectivity |
| PC-to-router ping | Verify default gateway connectivity |
| DNS lookup | Verify domain name resolution |
| HTTP browser test | Verify internal website accessibility |
| Simulation Mode | Observe network packet transmission |

Test results and supporting screenshots are documented in the `testing/` and `screenshots/` directories.

## Repository Structure

```text
small-office-network-security/
│
├── README.md
│
├── network-design/
│   ├── ip-addressing-table.md
│   └── network-topology.md
│
├── configuration/
│   ├── router-configuration.txt
│   ├── switch-configuration.txt
│   └── server-configuration.md
│
├── security/
│   ├── security-measures.md
│   └── security-recommendations.md
│
├── testing/
│   ├── connectivity-tests.md
│   └── troubleshooting.md
│
├── screenshots/
│
└── packet-tracer/
    └── small-office-network.pkt
```

## Author

**Marumo Lerato Matome**
