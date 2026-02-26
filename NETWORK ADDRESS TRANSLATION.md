**Network Address Translation**



**## Overview ##**



This lab demonstrates

-- NAT Configuration

-- Layer 3 Routing

-- Verification

-- DHCP



**## Topology ##**



\- Lab 1 -

* 1 Router
* 2 Switches
* 3 PCs
* 1 Server



\- IP Addressing -

* LAN1: 192.168.100.0/24
* Gateway: 192.168.100.1



* LAN2: 10.0.0.0/24
* Gateway: 10.0.0.1



* Public IP: 30.30.30.1



\- Lab 2 -

* Routers
* 2 Switches
* 1 PC
* 3 Laptops
* 1 Server



\- IP Addressing -

* LAN1USERS: 192.168.0.0/24
* Gateway: 192.168.0.1



* LAN2R\&D: 10.100.0.0/29
* Gateway: 10.100.0.1



* Public IP: 30.30.30.1



**## Notes \& Skills Demonstrated ##**

**--** NAT Configuration

-- Troubleshooting

-- RIP Configuration

-- DHCP

-- Verification

-- Lab 1 \& 2 primarily demonstrated the ability to configure the network such that the outside network only saw the public IP address of the private internal network. For lab 2 RIP was configured for layer 2 routing as well as DHCP. When NAT was configured and tested the reply pings were for the public IP address only. This was observed for both Lab 1 \& 2.

