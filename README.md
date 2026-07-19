#  Smart Factory Enterprise Network Simulation

## Overview

This project simulates a secure Smart Factory Enterprise Network using Cisco Packet Tracer. It demonstrates how enterprise networks are designed using VLAN segmentation, inter-VLAN routing, DHCP, DNS, wireless networking, ACL-based security, and NAT for Internet connectivity.


## Features

- VLAN Segmentation
- Router-on-a-Stick
- Inter-VLAN Routing
- DHCP Server
- DHCP Relay (IP Helper Address)
- DNS Server
- Internal Web Server
- Wireless LAN (WPA2-PSK)
- Access Control Lists (ACLs)
- NAT/PAT
- Internet Simulation



## Network Topology

![Network Topology](Screenshots/Network%20Topology.png)



## VLAN Configuration

| VLAN | Department | Network |
|------|------------|---------|
| 10 | Administration | 192.168.10.0/24 |
| 20 | Engineering | 192.168.20.0/24 |
| 30 | Production | 192.168.30.0/24 |
| 40 | Servers | 192.168.40.0/24 |
| 50 | Maintenance | 192.168.50.0/24 |



## Technologies Used

- Cisco Packet Tracer
- Cisco IOS CLI
- VLANs
- DHCP
- DNS
- ACL
- NAT/PAT
- Router-on-a-Stick
- WPA2 Wireless Security



## Testing Performed

- Successful inter-VLAN communication
- Automatic IP assignment using DHCP
- DNS name resolution
- Internal website access
- Wireless client connectivity
- ACL verification
- NAT translation and Internet simulation



## Project Structure

```
Configurations/
Screenshots/
Packet-Tracer/
README.md
```



## Author

**Hinduja Gowda**

Electronics and Communication Engineering (ECE)
