# `tcpip.sys`

[Back to index](../README.md) · [Українська версія](tcpip.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `15034904B98C49B959C848F48ADA109E86F6EE97BA5422FF9A6A61D848C6AF39` | `5DA4FD9E08F97B78A37C367134B251FC02A8C8D8` | `CF88CBCD74AF47D7C98F99F4D9A7BA4E` |

## Metadata

- **Filename:** `tcpip.sys`
- **Size:** 3474920 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** TCP/IP Driver
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `page locking`, `process address-space attach`, `process handle access`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmProbeAndLockPages`, `ZwOpenProcess`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.
