# Enterprise Campus Network — CCNP ENCOR Lab

A hands-on enterprise network simulation based on CCNP ENCOR design principles. The lab explores hierarchical design, dynamic routing, gateway redundancy, segmentation, and access-layer security.

## Architecture

```text
ISP
 |
EDGE Router (NAT/PAT)
 |
Dual L3 CORE Switches (EtherChannel)
 |
Dual L3 DISTRIBUTION Switches (HSRP / Inter-VLAN Routing)
 |
L2 ACCESS Switches (VLANs / Port Security)
```

## Technologies and protocols

- Cisco IOS
- OSPF dynamic routing
- VLAN segmentation and inter-VLAN routing
- HSRP gateway redundancy
- EtherChannel
- STP/RSTP
- NAT/PAT
- DHCP Snooping and Port Security

## Lab scope

- Segmented HR, Finance, IT, and Sales networks
- Redundant core/distribution design
- Dynamic routing and failover behavior
- Security controls at the access layer

## Status

Completed hands-on lab. This repository currently serves as the public documentation record; sanitized device configurations and topology exports will be added as they are prepared for publication.

Portfolio: https://github.com/mohammed-goraney/my-portfolio
