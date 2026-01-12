AutoBuild Lanka – Enterprise Network Design & Troubleshooting Project
📌 Project Overview

This project presents the design, implementation, monitoring, and troubleshooting of a secure and scalable enterprise network for AutoBuild Lanka, a multi-site organisation operating between Hambantota (manufacturing branch) and Colombo (head office).

The network solution is designed to support high availability, secure inter-branch communication, redundancy, and future scalability, while aligning with industry best practices and academic learning outcomes.

🎯 Project Objectives

Design a robust LAN architecture with VLAN segmentation and redundancy

Implement Layer 2 and Layer 3 fault tolerance

Establish secure WAN connectivity using VPN technologies

Apply dynamic routing protocols for resilience

Deploy network monitoring and troubleshooting methodologies

Document and resolve realistic LAN and WAN fault scenarios

Produce professional technical documentation and presentation

🏗️ Network Design Architecture

Design Model: Three-Tier Hierarchical Network (Core, Distribution, Access)

LAN Segmentation: VLAN-based departmental separation

Inter-VLAN Routing: SVIs on Layer 3 switches

Layer 2 Redundancy:

RSTP / MSTP

EtherChannel (LACP)

Layer 3 Redundancy:

HSRP for default gateway failover

Dynamic Routing:

OSPF for LAN and WAN routing

🌐 WAN & VPN Implementation

WAN Type: Internet-based WAN

VPN Technology: Site-to-Site IPsec VPN

Security Features:

Encrypted inter-branch traffic

Peer authentication

Data integrity protection

Routing over WAN: OSPF over IPsec tunnel

This approach provides enterprise-grade security with cost efficiency and scalability.

🔐 Security & Access Control

Access Control Lists (ACLs):

Role-based access enforcement

HR users permitted to access File Servers

Production users restricted based on policy

Security Best Practices:

VLAN isolation

Disabled default VLAN (VLAN 1)

Least-privilege access model

📊 Network Monitoring & Troubleshooting
Monitoring Practices

Interface status monitoring

Routing table verification

VPN tunnel monitoring

Establishment of network performance baselines

Troubleshooting Methodology

OSI-layered troubleshooting approach

Evidence-based diagnostics using Cisco IOS show commands

Structured documentation of faults and resolutions

🛠️ Troubleshooting Scenarios Covered
Scenario (a)

Issue: Hambantota users unable to access Colombo servers
Root Cause: Missing OSPF route advertisement
Resolution: Corrected OSPF network configuration

Scenario (b)

Issue: HR users can access File Servers, Production users cannot
Root Cause: Intentional ACL-based policy enforcement
Resolution: Policy verified and validated

🧪 Tools & Technologies Used

Cisco Packet Tracer

Cisco IOS CLI

Routing Protocols: OSPF

Redundancy Protocols: HSRP, RSTP, LACP

VPN Technologies: IPsec

Monitoring & Diagnostic Commands (show ip route, show ip ospf, show access-lists, etc.)
