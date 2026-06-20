# Office Network Design

## Project Overview
! [ Network Topology](screenshots/topology.png)

This project demonstrates the design and implementation of a small office network using Cisco Packet Tracer.

The network separates Staff and Guest users using VLANs while providing dynamic IP address assignment (DHCP). Inter-VLAN communication is enabled using Router-on-a-Stick.

## Objectives

- Separate Staff and Guest devices using VLANs.
- Configure Router-on-a-Stick.
- Configure DHCP.
- Test network connectivity.
- Restricted Guest VLAN access to the STAFF VLAN using an Access Control List (ACL) 

## Technologies Used

- Cisco Packet Tracer
- Cisco IOS CLI
- VLANs
- DHCP
- Router-on-a-Stick
- Access Control Lists (ACLs) 

## Skills Demonstrated

- Network Design
- VLAN Configuration
- DHCP Configuration
- Router Configuration
- Network Troubleshooting
- Network Security & Access Control Configuration

# What I Configured

In this project, I designed and configured a small office network in Cisco Packet Tracer. I created separate VLANs for Staff and Guest users, configured trunking between the switch and router, implemented Router-on-a-Stick for inter-VLAN routing, and configured DHCP to automatically assign IP addresses to devices. After completing the configuration, I verified connectivity using Cisco IOS verification commands and ping tests. I also configured an extended ACL to restrict the Guest VLAN from accessing the Staff VLAN, then verified the restriction using ping test.

## Network Configuration

- Created VLAN 10 (Staff)
- Created VLAN 20 (Guest)
- Assigned switch ports to the appropriate VLANs
- Configured an 802.1Q trunk between the switch and router
- Configured router subinterfaces using encapsulation dot1Q
- Configured DHCP pools for both VLANs
- Configured an extended ACL (ACL 100) to deny traffic from the Guest VLAN to the Staff VLAN, applied inbound on the Guest subinterface
- Verified connectivity between devices


## The following commands were used to verify the network configuration:

- show vlan brief
- show ip interface brief
- show running-config
- show ip dhcp binding
- ping

## Screenshots
The repository includes screenshots showing:

- Network topology
- VLAN configuration
- Router subinterface configuration
- IP interface configuration
- Connectivity tests
