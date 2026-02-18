# ccna-labs

# Networking Labs (CCNA / Packet Tracer)

This repo contains hands-on networking labs completed while studying for CCNA 200-301 (v1.1).
Focus: building, verifying, and troubleshooting small networks (not just following steps). Lab scenarios are taken from the [Jeremy's IT Lab CCNA 200-301 study playlist on YouTube.](https://www.youtube.com/playlist?list=PLxbwE86jKRgMpuZuLBivzlM8s2Dk5lXBQ)

## What you'll find here
- Packet Tracer (.pkt) files for each lab
- A short writeup per lab (goal, topology, key configs, verification, break/fix notes)
- Screenshots and command outputs where relevant

## Lab index
| Lab | Topic | What it demonstrates | Artifacts |
|---|---|---|---|
| 01 | IPv4 addressing & basic connectivity | IP plan, default gateway logic, verification workflow | `labs/01_ipv4_basics/` |


## How to use this repo
1. Install Cisco Packet Tracer.
2. Open the `.pkt` file in each lab folder, if available.
3. Read the lab writeup (`README.md` inside the lab folder) for:
   - IP plan / topology
   - config highlights
   - verification checklist
   - break/fix scenario and troubleshooting notes

## Verification workflow (used across labs)
Common checks include:
- `show ip interface brief`
- `show vlan brief`
- `show interfaces trunk`
- `show spanning-tree`
- `show ip route`
- `show ip ospf neighbor`
- `show access-lists`
- `ping`, `traceroute`

## Repo structure
- `labs/` → one folder per lab
- `images/` or `screenshots/` → screenshots used in writeups
- `templates/` → lab writeup template

## Notes
- These labs are intentionally small and repeatable. 
- Most labs includes at least one "break/fix" case to practice troubleshooting rather than only configuration.
- Earlier labs are more about understanding the fundamentals of a topic and learning Cisco's system. If there is no issue to solve, I will not include .pkt files and lab reports will look more like study logs. Files are included starting from Lab 6.
- Jeremy's lab videos are full walkthroughs. I do not watch them in the course of doing each lab.