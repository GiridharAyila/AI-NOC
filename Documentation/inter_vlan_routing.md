# Inter-VLAN Routing (Router-on-a-Stick)

## Router Configuration

Configured Router R1 with IEEE 802.1Q subinterfaces for VLANs:

* VLAN 10 – ADMIN
* VLAN 20 – FACULTY
* VLAN 30 – STUDENTS
* VLAN 40 – SERVERS
* VLAN 99 – MANAGEMENT

## IPv4 Addressing

Each VLAN was assigned a separate /24 subnet.

## Verification

* Verified router subinterfaces using `show ip interface brief`
* Verified host configuration using `ipconfig`
* Successfully tested communication between devices using `ping`
