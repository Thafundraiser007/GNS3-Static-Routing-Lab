# GNS3-Static-Routing-Lab
GNS3 lab demonstrating IP addressing, static routing, and end-to-end connectivity across Three routers


## Overview
This lab demonstrates the configuration of three routers in GNS3 using static routing. Each router was assigned IP addresses on its interfaces, and static routes were configured to allow communication between all networks.

## Objectives
- Configure router interfaces with IP addresses
- Verify interface connectivity
- Configure static routes
- Test end-to-end communication
- Troubleshoot routing issues

## Topology

R1 ---- R2 ---- R3

## IP Addressing

| Device | Interface | IP Address |
|----------|----------|----------|
   | R1 | fa0/0 | 192.168.10.1 |
   | R2 | fa0/0 | 192.168.10.2 |
   | R2 | fa1/0 | 192.168.11.1 |
   | R3 | fa0/0 | 192.168.11.2 |


## Configuration Steps

### 1. Configure Router Interfaces
Assigned IP addresses to all router interfaces and enabled them using the "no shutdown" command.

### 2. Configure Static Routes
Created static routes on each router to reach remote networks through the correct next-hop addresses.

### 3. Verify Connectivity
Used:
- "show ip interface brief"
- "show ip route"
- "ping"

to verify proper configuration and connectivity.

## Results

✅ All router interfaces came up successfully.

✅ Static routes were installed correctly.

✅ End-to-end communication was established between all networks.

✅ Ping tests completed successfully with no packet loss.

## Skills Demonstrated

- Network Design
- IP Addressing
- Cisco Router Configuration
- Static Routing
- Network Troubleshooting
- Connectivity Testing
- GNS3

