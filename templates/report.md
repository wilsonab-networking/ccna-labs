# Lab Report — <LAB TITLE>

**Topic:** <e.g., VLANs & Trunking>  
**Tool:** <Packet Tracer / CML / EVE-NG>  
**Date:** <YYYY-MM-DD>  
**Time spent:** <e.g., 45 min>  
**Difficulty:** <Easy / Medium / Hard>

---

## 1) Objective
- <What you intended to build/verify in 1–3 bullets>

## 2) Topology
![Topology diagram](./screenshots/topology.png)

**Devices**
- SW1: <model/role>
- SW2: <model/role>
- R1: <model/role>
- PC1/PC2: <role>

## 3) Addressing Plan
| Node | Interface | IP / Prefix | VLAN | Gateway | Notes |
|---|---|---:|---:|---:|---|
| PC1 | NIC | 192.168.10.10/24 | 10 | 192.168.10.1 | |
| SW1 | SVI (VLAN10) | 192.168.10.2/24 | 10 | — | mgmt only |
| R1 | G0/0.10 | 192.168.10.1/24 | 10 | — | subinterface |

## 4) Requirements
- [ ] <Requirement 1 (e.g., VLAN 10 and 20 must communicate through R1)>
- [ ] <Requirement 2 (e.g., Trunk between SW1 and SW2)>
- [ ] <Requirement 3 (e.g., ACL blocks VLAN 20 from VLAN 10)>

## 5) Key Configuration (highlights only)
> Keep this to the minimum commands that matter. Do not paste full configs unless necessary.

### SW1
```text
<commands/snippets here>

### SW2
```text
<commands/snippets here>

### R1
```text
<commands/snippets here>


