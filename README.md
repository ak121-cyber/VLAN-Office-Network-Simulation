# VLAN Office Network Simulation

## Overview

This project demonstrates the design and configuration of a VLAN-based office network using Cisco Packet Tracer. The network is divided into separate departments using VLAN segmentation and inter-VLAN routing.

## Network Components

* 1 Router
* 1 Switch
* 4 PCs

## VLAN Structure

| VLAN | Department | Network         |
| ---- | ---------- | --------------- |
| 10   | HR         | 192.168.10.0/24 |
| 20   | Sales      | 192.168.20.0/24 |

## Configuration Highlights

* VLAN creation and port assignment
* Trunk link between switch and router
* Inter-VLAN routing (Router-on-a-Stick)
* IP addressing and gateway configuration

## Verification

Network connectivity was verified using ping tests between devices across VLANs.

## Screenshots

Screenshots of topology, VLAN configuration, trunk configuration, and connectivity tests are included in the screenshots folder.

## Tools Used

Cisco Packet Tracer
