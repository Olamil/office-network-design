# Office Network Design

## Project Overview

This project demonstrates the design and implementation of a small office network using Cisco Packet Tracer.

The network separates Staff and Guest users using VLANs while providing dynamic IP address assignment (DHCP). Inter-VLAN communication is enabled using Router-on-a-Stick.

## Objectives

- Separate Staff and Guest devices using VLANs.
- Configure Router-on-a-Stick.
- Configure DHCP.
- Test network connectivity.

## Technologies Used

- Cisco Packet Tracer
- Cisco IOS CLI
- VLANs
- DHCP
- Router-on-a-Stick

## Skills Demonstrated

- Network Design
- VLAN Configuration
- DHCP Configuration
- Router Configuration
- Network Troubleshooting

# What I Configured

In this project, I designed and configured a small office network in Cisco Packet Tracer. I created separate VLANs for Staff and Guest users, configured trunking between the switch and router, implemented Router-on-a-Stick for inter-VLAN routing, and configured DHCP to automatically assign IP addresses to devices. After completing the configuration, I verified connectivity using Cisco IOS verification commands and ping tests.

## Network Configuration

Created VLAN 10 (Staff)
Created VLAN 20 (Guest)
Assigned switch ports to the appropriate VLANs
Configured an 802.1Q trunk between the switch and router
Configured router subinterfaces using encapsulation dot1Q
Configured DHCP pools for both VLANs
Verified connectivity between devices
Verification

## The following commands were used to verify the network configuration:

show vlan brief
show ip interface brief
show running-config
show ip dhcp binding
ping

## Screenshots
The repository includes screenshots showing:

Network topology
VLAN configuration
Router subinterface configuration
IP interface configuration
Connectivity tests
