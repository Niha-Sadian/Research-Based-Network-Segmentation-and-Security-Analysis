# Research-Based Network Segmentation and Security Analysis

## Project Overview

This project focuses on the research, design, and practical analysis of network segmentation and security in an enterprise network environment.

The main purpose of this project is to understand how network segmentation can isolate different groups of users and devices, reduce unnecessary network access, and improve overall network security.

The project combines theoretical research with a Cisco Packet Tracer-based network simulation to demonstrate the practical concepts of network segmentation.

## Network Segmentation

The network is divided into separate VLANs to logically isolate different groups within the organization.

  VLAN 10 — 192.168.10.0/24
  VLAN 20 — 192.168.20.0/24
  VLAN 30 — 192.168.30.0/24
  VLAN 40 — 192.168.40.0/24 — Guest Network

Inter-VLAN communication is configured using Router-on-a-Stick, allowing communication between different VLANs where permitted.

## Security Implementation

An Extended Access Control List  named GUEST-BLOCK has been configured to restrict Guest VLAN traffic from accessing internal network segments.

The ACL is designed to block Guest traffic toward:
192.168.10.0/24
192.168.20.0/24
192.168.30.0/24

The ACL configuration has been completed; however, its functional execution and complete traffic-blocking behavior are still under testing and verification.

Therefore, the project does not claim successful ACL enforcement until the expected behavior is fully validated.


## Practical Simulation

Cisco Packet Tracer is used to simulate the segmented network and perform connectivity testing between different network segments.

The simulation is used to analyze:

1.Communication between VLANs
2.Network isolation
3.Permitted and restricted traffic
4.Guest network access


Connectivity is tested using commands such as `ping` to observe communication between different network segments.

## Technologies and Tools

1.Cisco Packet Tracer
2.VLAN
3.Router-on-a-Stick
4.Inter-VLAN Routing
5.DHCP
6.Extended ACL
7.IP Addressing
8.Wireless Networking
9.TCP/IP

## Project Status

1.Network topology design — Completed
2.VLAN configuration — Completed
3.Inter-VLAN routing — Completed
4.DHCP configuration — Completed
5.Guest network configuration — Completed
6.ACL configuration — Completed
7.ACL traffic testing — Not Performed
8.Final security validation — Not Performed
