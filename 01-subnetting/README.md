# 01 - Subnetting

## Overview

This lab focuses on IPv4 subnetting and network address planning.

The goal is to divide a larger network into smaller subnets using
Variable Length Subnet Masking (VLSM) based on the number of hosts
required by each department.

---

## Objectives

- Calculate IPv4 subnets using CIDR notation
- Determine network and broadcast addresses
- Calculate usable host ranges
- Apply VLSM to efficiently allocate addresses
- Create an IP addressing plan for a small business network
- Document the reasoning behind the subnet design

---

## Scenario

A small company has been allocated the following IPv4 network:

`192.168.10.0/24`

The network must support four departments:

| Department | Required Hosts |
|---|---:|
| Administration | 30 |
| Development | 50 |
| Sales | 20 |
| Support | 10 |

The available address space must be divided efficiently using VLSM.

---

## Requirements

For each department, determine:

- Network address
- CIDR prefix
- Subnet mask
- First usable address
- Last usable address
- Broadcast address
- Number of usable hosts

The final addressing plan should accommodate all required hosts while
minimising unused address space.

---

## Topology

No physical topology is required for this lab yet.

The focus of this lab is network planning and subnet calculation.

---

## Addressing Plan

See [`addressing/addressing-table.md`](addressing/addressing-table.md).

---

## Calculations

See [`addressing/subnet-calculations.md`](addressing/subnet-calculations.md).

---

## Verification

The calculations will be manually verified by checking:

- Network boundaries
- Broadcast addresses
- Usable host ranges
- Overlapping address ranges
- Whether each subnet provides enough usable addresses

---

## What I Learned

### VLSM

_Add your explanation after completing the lab._

### Network Address

_Add your explanation._

### Broadcast Address

_Add your explanation._

### Usable Host Range

_Add your explanation._

---

## Challenges / Troubleshooting

Document any mistakes or incorrect subnet calculations encountered
during the lab.

---

## Key Takeaways

_Add a few points summarising what you learned from the exercise._
