**Floating Static Route + VLANS**



**## Overview ##**



This lab demonstrates

-- Layer 3 routing

-- Subnetting

-- VLAN creation

-- Troubleshooting



**## Topology ##**



\- Lab 1 -

* 2 Routers
* 2 Switches
* 2 Laptops



\- IP Addressing -

* VLAN10: 172.16.0.0/24
* Gateway: 172.16.0.10



* VLAN20: 172.16.100.0/24
* Gateway: 192.16.100.10



* P2P Link: 10.0.0.0/30



\- Lab 2 -

* 3 Routers
* 3 Switches
* 3 Laptops



\- IP Addressing -

* VLAN10: 192.168.0.0/30
* Gateway: 192.168.0.1



* VLAN20:192.168.100.0/30
* Gateway: 192.168.100.1



* VLAN30: 192.168.150.0/30
* Gateway: 192.168.150.1



* P2P Links: 10.0.0.0/29, 10.0.10.0/29, 10.0.100.0/29



**## Notes \& Skills Demonstrated ##**



**--** Floating static route configuration

-- OSPF configuration

-- Layer 3 troubleshooting

-- VLAN configuration

-- Verification

-- Documentation

-- R.O.A.S.

-- The goal in lab 1 \& 2 was for the end devices to communicate via floating static route and OSPF. The methodology was to first create VLANS, floating static routes, and then configure OSPF followed by a test ping. 

-- In lab 2 the initial pings were not successful. The subnet mask on VLANs were changed and the administrative distance on the floating static route was adjusted as well. After adjustments were made the network could communicate between Vlans. This lab demonstrated a further depth in scope of layer 3 routing; recalling that the router will choose the route with the lowest cost path which in this case was OSPF (AD of 110) compared to the floating static routes configured (AD of 200).



