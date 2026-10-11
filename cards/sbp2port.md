# `sbp2port.sys`

[Back to index](../README.md) · [Українська версія](sbp2port.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `7027E3FE0FB1F3BD5600927ECA4A6D0C763FF3695F14B59A757B668BB9D6E55B` | `D3EF60831401036B748853ACBFF1714BE4A17939` | `B611E8E1919F41054E750CDA92AA2485` |

## Metadata

- **Filename:** `sbp2port.sys` (Identical copies: `sbp2port_1.sys`)
- **Size:** 148912 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** SBP-2 Protocol Driver
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `page locking`, `process address-space attach`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmProbeAndLockPages`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.
