---

# **ITNET02 Enterprise Network – Case Study**

This repository contains the Phase 2 design and implementation of the ITNET02 enterprise network case project. The project extends the Phase 1 network with expanded VLAN segmentation, centralized DHCP services, enhanced access control, and multiple layers of network security tool configuration.

The objective is to demonstrate scalable enterprise network design principles in simulation using Cisco Packet Tracer while documenting logical and physical topologies, addressing models, and security implementations.

---

## **📌 Phase 2 Goals**

* Strengthen infrastructure security and traffic control
* Maintain scalability for future growth of users and devices
* Improve manageability through consistent naming conventions and addressing
* Implement switch/router security features
* Apply VLAN mapping across workgroups and servers
* Validate security policies through access control matrix testing

---

## **📍 IP Addressing + DHCP**

The network assigns addressing dynamically via DHCP for most user devices, while critical systems are given static IPs.

### Key elements:

* 6 VLANs/subnets allocated based on departmental needs
* Host allocations doubled to support scalability
* DHCP pools per VLAN
* Routers and servers statically addressed for stability
* Structured naming conventions for workstations and infrastructure

---

## **🏗 Physical Topology**

The diagram aligns with the organizational floor plan. Key principles:

* All cabling routed along walls for protection + manageability
* Networking devices centralized inside a secure server room
* Structured cable management between switches, routers, and endpoints

---

## **🔀 Logical Topology + Routing**

* VLANs grouped per department
* Router-on-a-stick inter-VLAN routing
* VTP propagated VLAN configurations
* Modular scalability: new departments can be added by extending switching fabric + router subinterfaces

---

## **🔒 Security Implementation**

Several network security layers were applied to prevent unauthorized access and maintain stability:

### Enforcement measures include:

* **Strong passwords** across devices
* **Login attempt blocking** to mitigate brute force attacks
* **Shutdown of unused ports**
* **SSH for secure administrative access**
* **Port security features**:

  * Restrict MAC address limits
  * Sticky MAC learning
  * VLAN hopping mitigation
  * Native VLAN protection
* **DHCP Snooping**
* **Dynamic ARP Inspection**
* **ACL-based access control matrix**

  * Restricts lateral movement across departments
* **Secure storage of physical infrastructure**

---

## **📁 Documentation Included**

* IP addressing tables
* Logical topology
* Physical floor plan layouts
* VLAN assignments
* Device connection table
* ACL rules + justification
* Password and VTP summaries
* SSH authentication settings

---

## **🧪 Validation & Testing**

Security + access enforcement tested through:

* ping/route adjacency testing
* VLAN isolation checks
* DHCP/DNS assignment validation
* ACL permission / deny matrix verification
* Wireless not yet required in Phase 2 specification

---

## **🛠 Tools + Technologies**

* Cisco Packet Tracer
* IPv4 subnetting
* VLANs + VTP
* Router-on-a-stick
* DHCP
* ACLs
* DHCP Snooping
* Dynamic ARP Inspection
* SSH remote administration

---
