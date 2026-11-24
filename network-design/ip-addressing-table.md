# IP Addressing Documentation

## Network Information

| Parameter | Configuration |
|---|---|
| Network Address | 192.168.10.0 |
| Subnet Mask | 255.255.255.0 |
| CIDR | /24 |
| Default Gateway | 192.168.10.1 |
| Broadcast Address | 192.168.10.255 |
| DNS Server | 192.168.10.10 |

## Device Addressing

| Device | IP Address | Subnet Mask | Default Gateway |
|---|---|---|---|
| Office Router | 192.168.10.1 | 255.255.255.0 | N/A |
| Office Switch | 192.168.10.2 | 255.255.255.0 | 192.168.10.1 |
| Office Server | 192.168.10.10 | 255.255.255.0 | 192.168.10.1 |
| Administration PC | 192.168.10.11 | 255.255.255.0 | 192.168.10.1 |
| Finance PC | 192.168.10.12 | 255.255.255.0 | 192.168.10.1 |
| IT Support PC | 192.168.10.13 | 255.255.255.0 | 192.168.10.1 |

## Addressing Method

Static IP addressing was selected to provide predictable addresses for the network infrastructure and employee devices.

Each device has a unique IPv4 address within the same subnet.

## Network Explanation

The `/24` prefix means that the first 24 bits identify the network portion of the address.

The remaining 8 bits identify individual hosts.

The subnet supports 254 usable IPv4 host addresses.
