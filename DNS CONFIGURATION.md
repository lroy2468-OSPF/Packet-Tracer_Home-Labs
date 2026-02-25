**DNS Configuration**



**## Overview ##**



This lab demonstrates

-- DNS Configuration

-- IP Addressing

-- Trouble shooting

-- Verification



**## Topology ##**



\- Lab 1 -

* 2 Routers
* 2 Switches
* 2 Laptops
* 1 Server



\- IP Addressing -

* LAN1: 192.168.0.0/24
* Gateway: 192.168.0.1



* LAN2: 192.168.200.0/24
* Gateway: 192.168.200.1



* P2P Link: 10.0.0.0/30



\- Lab 2 -

* 3 Routers
* 3 Switches
* 5 Laptops
* 1 PC
* 1 Server



\- IP Addressing -

* LAN1USERS: 192.168.0.0/24
* Gateway: 192.168.0.1



* LAN2ENGINEERING: 192.168.100.0/24
* Gateway: 192.168.100.1



* LAN3EXEC: 192.168.200.0/24
* Gateway: 192.168.200.1



* P2P Links: 10.0.0.0/30, 10.1.0.0/29



**## Notes \& Skills Demonstrated ##**

**--** Troubleshooting

-- Verification

-- DNS Configuration

-- DHCP

-- Documentation

-- Layer 3 Routing

-- The goal of Lab 1 was to ping the Domain name and IP address of other end devices. Lab 1 was configured with RIP routing. Initially domain names did not ping until they were manually configured on the server. Following the adjustments all network and network names were able to communicate.

-- Lab 2 was similar although the routing protocol used was OSPF. DNS and DHCP were configured and verified on LANs 1 \& 2. 3 LANs were used to replicate SOHO. All LANs communicated successfully.













