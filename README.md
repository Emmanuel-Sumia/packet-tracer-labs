# packet-tracer-labs
Welcome, everyone. This is my repo containing networking labs, mostly completed in Cisco Packet Tracer. Feel free to give feedback, guidance, and offer support. Thanks

# Network Routing Lab (Static, OSPF, EIGRP, BGP)

## Overview
This project demonstrates the implementation and comparison of multiple routing protocols in a multi-router network topology. The goal was to understand how different routing methods operate, how routers exchange information, and how traffic flows between networks.

## Topology
A consistent topology was used across all configurations:

LAN1 — R1 ===== R2 — LAN2
![70F4910B-8086-4A9B-823C-E7EACB2BFC9D_1_105_c](https://github.com/user-attachments/assets/802321bb-08e6-4bf6-be20-927400c021cd)


- LAN1: 192.168.10.0/24  
- LAN2: 192.168.20.0/24  
- WAN: 10.0.0.0/30  

## Protocols Implemented
- Static Routing  
- OSPF (Open Shortest Path First)  
- EIGRP (Enhanced Interior Gateway Routing Protocol) ( In progress )  
- BGP (Border Gateway Protocol)  (In progress)

Each protocol was and will be configured separately on the same topology to compare behavior, scalability, and routing decisions.

## Key Concepts Demonstrated
- Inter-network routing between LANs  
- Default gateway and packet forwarding  
- ARP (IP to MAC resolution within LANs)  
- Dynamic vs static routing  
- Routing table analysis and verification  
- Network segmentation and communication  

## Tools Used
- Cisco Packet Tracer  
- CLI (Command Line Interface)

## Verification
- Successful end-to-end connectivity using ICMP `ping.`  
- Routing tables verified using `show ip route.`  
- Protocol neighbors verified using appropriate commands  

## Outcome
Built a strong foundation in routing protocols and network communication by implementing and analyzing multiple routing strategies in a controlled lab environment.
