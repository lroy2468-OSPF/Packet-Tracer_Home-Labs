**Root Guard Configuration**



**## Overview ##**



This lab demonstrates

-- STP

-- DHCP

-- Troubleshooting



**## Topology ##**



\- Lab 1 -

* 1 Server
* 5 Laptops
* 2 Routers
* 5 Switches



\- IP Addressing -

* LAN2ENG: 192.168.200.0/30
* Gateway: 192.168.200.1



* LAN1USERS: 192.168.0.0/24
* Gateway: 192.168.0.1



* P2P Link: 172.16.0.0/29



**## Notes \& Skills Demonstrated ##**



-- Verification

-- OSPF Configuration

-- DHCP

-- Root Guard

-- This network consisted of configuring end devices as well as ensuring network communication. The routing protocol used was OSPF. A feature of Spanning Tree Protocol that was verified was Root Guard - ensuring that another switch with a superior BPDU does not accidently become the new root switch. Laptop configuration for LAN1USERS was through DHCP.



