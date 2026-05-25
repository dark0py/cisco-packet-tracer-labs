# cisco-packet-tracer-labs
# Lab 01 - Basic CLI and End-to-End Connectivity

## Objective
learning Cisco CLI and providing connection end-to-end.

## Networks

RED: 172.16.0.0/24
Router: 172.16.0.1
PCs: 172.16.0.2, 172.16.0.3

GREEN: 89.12.0.0/24
Router: 89.12.0.1
PCs: 89.12.0.2, 89.12.0.3

BLUE: 192.168.0.0/24
Router: 192.168.0.1
PCs: 192.168.0.2, 192.168.0.3

## What I configured
- Router hostnames
- IP addresses
- Switch management IPs
- PC IP settings
- Enable password
- MOTD banner
- Telnet on RED1
- SSH on BLUE1
- Ping tests

## Important commands
enable
configure terminal
hostname
interface
ip address
no shutdown
show ip interface brief
show running-config
copy running-config startup-config

## What I learned
Routers use IP addresses on physical interfaces.
Switches use VLAN 1 for management IP.
PCs need a default gateway to reach other networks.
