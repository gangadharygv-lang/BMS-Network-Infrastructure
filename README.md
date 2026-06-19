# Building Management System (BMS) Network Infrastructure

## Project Overview

This project implements a Building Management System (BMS) network using VLAN segmentation, Inter-VLAN Routing, trunking, and a centralized BMS Server.

## Technologies

- Cisco Packet Tracer
- VLANs
- Inter-VLAN Routing
- Layer 3 Switching
- IEEE 802.1Q Trunking

## VLAN Design

| VLAN | Purpose | Network |
|--------|----------|----------|
| 4 | P2 Users | 192.168.4.0/24 |
| 13 | P3 Users | 192.168.13.0/24 |
| 7 | P4 Users | 192.168.7.0/24 |
| 8 | P5 + BMS Server | 172.1.8.0/24 |
| 100 | Management | 192.168.14.0/24 |

## Features

- VLAN Segmentation
- Inter-VLAN Routing
- Management VLAN
- BMS Server Connectivity
- End-to-End Testing

## Verification

Successful communication verified between all VLANs and the centralized BMS Server.