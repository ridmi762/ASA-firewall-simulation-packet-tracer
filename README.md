# ASA Firewall Simulation (Router-Based) – Cisco Packet Tracer Lab

## Overview

This project demonstrates the deployment and basic configuration of a simulated Cisco ASA firewall environment using Cisco Packet Tracer. Because the ASA 5505 device in Packet Tracer has limited functionality and does not fully support all required commands, a Cisco router was configured to emulate core ASA firewall operations such as interface setup, routing, and access control lists (ACLs).

The router hostname was set to **ASA** to reflect its role within the network topology.

## Network Topology

* Internet Router (Outside Network)
* ASA (Router-based firewall simulation)
* Layer 2 Switch
* Three Inside PCs

## Objectives

* Configure ASA-like firewall interfaces:

  * Inside: 192.168.1.1/24
  * Outside: 203.0.113.1/24
  * Management: 192.168.99.1/24
* Establish basic connectivity between internal hosts and external network
* Implement static routing
* Apply security using Access Control Lists (ACLs)

## Implementation Steps

1. Deployed router acting as ASA firewall.
2. Configured hostname, enable secret, and console password.
3. Connected three PCs via switch on inside network.
4. Assigned IP addresses and default gateways.
5. Configured internet router (203.0.113.254).
6. Verified connectivity using ping tests.
7. Created ACL allowing only HTTP (port 80) outbound traffic.
8. Tested allowed (HTTP) and blocked (FTP) traffic.

## Key Concepts Demonstrated

* Network segmentation (Inside vs Outside)
* Firewall simulation
* Access Control Lists (ACL)
* Static routing
* Basic security policy enforcement

## Tools Used

* Cisco Packet Tracer
* Cisco CLI configuration

## Learning Outcome

This lab demonstrates fundamental firewall concepts including interface configuration, traffic filtering, and controlled network access using ACLs.

---

*This project was completed as part of university coursework to practice network security fundamentals.*

