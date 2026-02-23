**Spanning Tree Protocol**



**## Overview ##**



This lab demonstrates

* STP Configuration
* Trouble shooting
* Subnetting
* Routing configuration



**## Topology ##**



\- Lab 1 -

* 3 switches
* 3 routers
* 3 laptops



\- IP Addressing -

* Laptop 0: 10.1.0.0/30
* Gateway: 10.1.0.1



* Laptop 1: 10.1.1.0/30
* Gateway: 10.1.1.1



* Laptop 2: 10.0.0.0/30
* Gateway: 10.0.0.1



* WAN: 192.168.0.0/24



\- Lab 2 -

* 4 Switches
* 4 Routers
* 4 Laptops



\- IP Addressing -

* User 1: 192.168.0.0/30
* Gateway: 192.168.0.1



* User 2: 192.168.10.0/30
* Gateway: 192.168.10.1



* User 3: 192.168.20.0/30
* Gateway: 192.168.20.1



* User 4: 192.168.30.0/30
* Gateway: 192.168.30.1



* WAN: 10.0.0.0/29



**## Notes \& Skills Demonstrated ##**



**-** Spanning Tree Protocol

\- Subnetting

\- RIP / OSPF routing

\- Verification

\- The goal was for all end devices to communicate with one another while enabling STP. After the network was up a non-root switch was set to administratively down. Communication was still enabled between all devices because of STP. Lab 1 was configured with RIP and lab 2 with OSPF.







