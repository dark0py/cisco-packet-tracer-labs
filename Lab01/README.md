# Lab 01 - RED Network

## Objective
Configuring a simple network using Cisco Packet Tracer.

## Devices
- Router RED1
- Switch 2960
- RED_PC1

## IP Addressing

Router RED1:
172.16.0.1/24

PC:
172.16.0.2/24

Gateway:
172.16.0.1

## Configured
- Router hostname
- Router interface IP
- no shutdown
- PC IP configuration
- Cabling
- Ping connectivity

## Important Commands

enable
configure terminal
interface g0/2
ip address 172.16.0.1 255.255.255.0
no shutdown
show ip interface brief
ping

## What I Learned
- How to configure a Cisco router
- How to troubleshoot connectivity
- Difference between down/down and up/up
- Basic Packet Tracer cabling
