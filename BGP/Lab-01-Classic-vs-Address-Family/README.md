Lab 01 — Classic BGP vs. Address-Family Configuration

Objective

The objective of this lab is to configure eBGP between Cisco routers using two configuration methods:

Traditional (classic) BGP configuration

IPv4 unicast address-family configuration

The lab will demonstrate how both methods establish BGP neighbor relationships and exchange IPv4 routing information.

Lab Environment

Platform: Cisco Modeling Labs (CML)

Routing Protocol: BGP

Configuration Methods: Classic BGP and IPv4 Address-Family

Network Topology

Topology screenshot will be added after completing the lab.

Phase 1 — Classic BGP Configuration

Configuration

Router configurations will be uploaded to the configs folder.

Verification

The following commands will be used:

show bgp ipv4 unicast summary

show bgp ipv4 unicast

show ip route bgp

show running-config | section router bgp

Results

To be completed after testing.

Phase 2 — Address-Family Configuration

Configuration

Reconfigure BGP using address-family ipv4 unicast and explicitly activate the neighbors.

Verification

Repeat the verification commands from Phase 1 and compare the results.

Results

To be completed after testing.

Configuration Comparison

Feature

Classic BGP

Address-Family BGP

Neighbor configuration

Global BGP mode

Global BGP mode

IPv4 network statements

Global BGP mode

IPv4 address-family mode

Neighbor activation

Automatic by default

Explicit when default IPv4 activation is disabled

IPv4 route exchange

To be verified

To be verified

Troubleshooting

Document any issues encountered, commands used to investigate, and how they were resolved.

Key Takeaways

Summarize what you learned after completing both phases.
