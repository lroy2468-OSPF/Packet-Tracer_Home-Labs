**VLAN Configuration**



**## Overview ##**



This lab demonstrates

* Subnetting
* Troubleshooting
* Vlan configuration on Router and Switch



**## Topology ##**



\- Lab 1 -

4 Routers

4 Switches

4 PC's



\- IP Addressing -

Sales: 192.168.10.0/24

Vlan 10 Gateway: 192.168.10.1



Exec: 192.168.20.0/24

Vlan 20 Gateway: 192.168.20.1



HR: 192.168.30.0/24

Vlan 30 Gateway: 192.168.30.1



ENG: 192.168.10.0/24

Vlan 40 Gateway: 192.168.40.1



Point-to-point links



\- Lab 2 -

2 Routers

2 Switches

2 PC's



\- IP Addressing -



Sales: 172.16.10.0/24

Vlan 10 Gateway: 172.16.10.1



ENG: 172.16.20.0/24

Vlan 20 Gateway: 172.16.20.1



Point-to-point links





**## Notes \& Skills Demonstrated ##**



**-** Switchport configuration on switches

\- Router on a Stick (ROAS)

\- Troubleshooting

\- Static routing

\- Subnetting / Private IP Addressing

\- Documentation

\- Verification

\- The goal was for all PCs to communicate with Vlan creation and static routing. After initial Vlan creation most ping attempts were unsuccessful. After troubleshooting I found that too many sub-interfaces were created and up on each router. After fix all PCs were able to ping one another.  













