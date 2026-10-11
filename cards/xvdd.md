# `xvdd.sys`

[Back to index](../README.md) · [Українська версія](xvdd.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `6EBE33FE986BD78211FAA71B1F44BA651D4708E1E7197F797136BF4C73253A65` | `099A3F81652917DB8FE0B719BF63FF87A3A665F1` | `4B02439CB80BA8E3EBBF6D55229F7D51` |

## Metadata

- **Filename:** `xvdd.sys`
- **Size:** 696048 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft Gaming Filesystem Driver
- **Description:** XVD Disk Driver
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** yes · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `page locking`, `process address-space attach`, `process lookup`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmProbeAndLockPages`, `PsLookupProcessByProcessId`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.
