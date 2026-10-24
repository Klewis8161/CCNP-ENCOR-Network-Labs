
# Lab 01 — Classic BGP vs. Address-Family Configuration

## Objective

Configure eBGP between Cisco routers using two methods:

1. Traditional (classic) BGP configuration
2. IPv4 unicast address-family configuration

The goal is to verify that both methods establish BGP neighbors and exchange IPv4 routing information.

## Lab Environment

- **Platform:** Cisco Modeling Labs (CML)
- **Routing Protocol:** BGP
- **Configuration Methods:** Classic BGP and IPv4 Address-Family

## Network Topology

*Topology screenshot will be added after completing the lab.*

## Phase 1 — Classic BGP Configuration

### Configuration

Router configurations will be uploaded to the `configs` folder.

### Verification

```cisco
show bgp ipv4 unicast summary
show bgp ipv4 unicast
show ip route bgp
show running-config | section router bgp
```

### Results

*To be completed after testing.*

## Phase 2 — Address-Family Configuration

### Configuration

Reconfigure BGP using `address-family ipv4 unicast` and explicitly activate the neighbors.

### Verification

Repeat the verification commands from Phase 1.

### Results

*To be completed after testing.*

## Troubleshooting

*Document any issues encountered and how they were resolved.*

## Key Takeaways

*Summarize what you learned.*
  
