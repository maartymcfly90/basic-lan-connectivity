# Basic Lan Connectivity
## Objectivty

Build a basic local area network using two PCs and a switch, configure IPv4 addressing, and verify connectivity using ICMP ping.

## Network Topology
- 2 PCs
- 1 Layer 2 switch
- Ethernet connections between each PC and the switch

## IP Addressing
| Device | Interface    | IP Address    | Subnet Mask  |
| ------ | ------------ | ----------    | -----------  | 
| PC1    | NIC          | 192.168.10.10 | 255.255.255.0|
| PC2    | NIC          | 192.168.10.20 | 255.255.255.0|
Both PCs are placed in the same /24 subnet:
Network 192.168.10.0 /24

## Implementation

1. Connected PC1 and PC2 to the switch.
2. Assigned IPv4 addresses to both PCs.
3. Verified that both PCs are in the same subnet
4. Tested connectivity using ping.
5. Rebuilt the topology from memory to verify understanding.

## Verfication

PC1 successfully pinged PC2

Example!

''' text
ping 192.168.10.20

Reply from 192.168.10.20
Reply from 192.168.10.20
Reply from 192.168.10.20
Reply from 192.168.10.20
