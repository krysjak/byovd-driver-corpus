# `hvservice.sys`

[Back to index](../README.md) · [Українська версія](hvservice.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `DE4919F9AE85B2B127F181EEFDE1A03970AED4B2B88958A05A8101F4E156A23B` | `4355804C20D0AF55FF753C4BE5934C01B9E04EDF` | `C03F0C573A2388A63A37B593C8C8433A` |

## Metadata

- **Filename:** `hvservice.sys` (Identical copies: `hvservice_1.sys`)
- **Size:** 99808 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** Hypervisor Boot Driver
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `process address-space attach`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.
