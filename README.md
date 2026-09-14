# Enterprise Network Project - DHCP & DNS Setup

This repository contains a Cisco Packet Tracer network simulation that demonstrates the implementation of dynamic IP addressing via DHCP and name resolution via DNS within an enterprise environment.

## 🌐 Network Topology

The network is segmented into two main subnets connected by a central router.

| Subnet ID | IP Network Range | Connected Devices | Description |
| :--- | :--- | :--- | :--- |
| Client Subnet | `192.168.10.0/24` | Router1, Switch0, PC0, PC1, PC2 | End-user workstations |
| Server Subnet | `200.10.20.0/24` | Router2, Switch1, R4-DNS, Server1 | Infrastructure and services |
| WAN Link | `12.12.21.0/30` | Router1, Router2 | Point-to-point link between routers |

