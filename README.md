# UWI St. Augustine Campus Network Design and Implementation

## Overview

This project simulates a university campus network for the University of the West Indies (UWI), St. Augustine Campus, using Cisco Packet Tracer. The network was designed using a hierarchical architecture and incorporates key networking technologies commonly found in enterprise environments.

The objective of this project was to create a secure, scalable, and efficient network infrastructure capable of supporting multiple academic departments, administrative units, staff offices, student laboratories, and university services across multiple campus locations.

## Project Objectives

* Design a campus-wide network using a hierarchical model.
* Implement logical network segmentation using VLANs.
* Configure inter-VLAN communication.
* Provide dynamic IP address allocation.
* Implement secure remote device management.
* Configure dynamic routing between network segments.
* Apply basic network security measures.
* Ensure connectivity between internal and external services.

## Network Features

### Hierarchical Network Design

The network follows a hierarchical structure consisting of access, distribution, and routing components to improve scalability, manageability, and performance.

### VLAN Segmentation

Separate VLANs were created to logically isolate departments, staff networks, administrative offices, and student laboratory environments. This improves security, reduces broadcast traffic, and simplifies network management.

### Inter-VLAN Routing

Router-on-a-Stick (ROAS) was implemented to enable communication between VLANs while maintaining logical separation between different network segments.

### Dynamic Host Configuration Protocol (DHCP)

A router-based DHCP service was configured to automatically assign IP addresses to client devices, reducing administrative overhead and simplifying device deployment.

### Routing

* RIPv2 was configured to facilitate dynamic routing throughout the internal network.
* Static routing was implemented where appropriate to provide connectivity to external resources and services.

### Security

Several security mechanisms were implemented throughout the network, including:

* SSH for secure remote administration
* Switch port security
* VLAN-based segmentation
* Controlled access between network segments

### Server Infrastructure

The network includes internal servers that provide university services, as well as connectivity to externally hosted services.

## Technologies Used

* Cisco Packet Tracer
* VLAN Configuration
* 802.1Q Trunking
* Router-on-a-Stick (ROAS)
* DHCP
* RIPv2
* Static Routing
* SSH
* Switch Port Security
* IP Addressing and Subnetting
* Hierarchical Network Design

## Testing and Verification

The following tests were performed to verify functionality:

* End-to-end network connectivity
* Inter-VLAN communication
* DHCP address assignment
* Route propagation through RIPv2
* SSH remote access
* Server accessibility
* Port security enforcement
* Network troubleshooting and validation

## Skills Demonstrated

* Enterprise Network Design
* Routing and Switching
* VLAN Design and Implementation
* IP Addressing and Subnetting
* Dynamic Routing Protocols
* Network Security Fundamentals
* Cisco Device Configuration
* Infrastructure Deployment
* Network Troubleshooting
* Technical Documentation



