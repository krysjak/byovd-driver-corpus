# `USBXHCI.SYS`

[Back to index](../README.md) · [Українська версія](USBXHCI.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `AFF0F88D0B3908BFA349048F4E1586B1D06F5FB6237C050FFD3A3BF9898A4A48` | `B66CE5CD71F0AEA9B760E3E864F56B9FDEFB5C6A` | `ED69C801E98FC2E8F3671B362EBECC9D` |

## Metadata

- **Filename:** `USBXHCI.SYS` (Identical copies: `USBXHCI_1.SYS`)
- **Size:** 792032 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** USB XHCI Driver
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11 · **Documented:** 2024-09-10
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** In the wild
- **Score:** 0 · **MITRE:** T1068

## Capability profile

**Primitives:** `MDL allocation`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmMapIoSpaceEx`

## Documented usage (LOLDrivers)

**Description:** Sophos, from time to time, has observed a threat actor deploy variants of Poortry on different machines within a single estate during an attack. These variants contain the same payload, but signed with a different certificate than the driver first seen used during the attack.

```
sc.exe create driver_ef9d653a.sys binPath=C:\windows\temp\driver_ef9d653a.sys type=kernel && sc.exe start driver_ef9d653a.sys
```

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.
