# Lab 04: Understanding Network and Port Address Translation

**Module:** M04 | **Course:** IT128 | **Date:** September 20, 2025

## Tools Used
- VyOS Edge Router
- GNS3
- NDG NetLab

## What I Did
Configured NAT on a VyOS Edge router by setting up internal hosts,
verifying connectivity, and applying three NAT techniques — Source NAT
(SNAT/masquerade) for outbound traffic, Destination NAT (DNAT) for
inbound redirection to PC3, and 1-to-1 NAT for dedicated bidirectional
mapping. Validated each configuration using ping tests and NAT
translation tables.

## Key Concepts
- Source NAT (SNAT) — masquerading internal IPs for outbound access
- Destination NAT (DNAT) — inbound traffic redirection
- 1-to-1 NAT — dedicated bidirectional IP mapping
- NAT translation table verification
- VyOS router configuration syntax

## Why This Matters
NAT is how virtually every home and enterprise network connects private
hosts to the public internet. Configuring SNAT, DNAT, and 1-to-1 NAT
on a real router emulates tasks performed by network engineers daily
and is a core Network+ exam topic.

## Screenshots
*See screenshots/ folder*
```
Commit message:
```
Add Lab 04
