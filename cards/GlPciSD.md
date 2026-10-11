# `GlPciSD.sys`

[Back to index](../README.md) · [Українська версія](GlPciSD.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `53A63122BCBC080B453DEF19277DC3F5EF4111B8426CA9AB53969A0826DFC71D` | `EF576992187B58B47837C3532349A091D641CCEF` | `9EF7CAF5A6FD81D6F7AFD0B2D1D21235` |

## Metadata

- **Filename:** `GlPciSD.sys`
- **Size:** 228592 bytes
- **Architecture:** 0x8664
- **Company:** Genesys Logic
- **Product:** Genesys Logic PCI CardReader Driver
- **Description:** Genesys Logic PCI CardReader Driver
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 125

## Capability profile

**Primitives:** `MDL allocation`, `page locking`, `physical address resolution`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmMapIoSpace`, `MmMapIoSpaceEx`, `MmProbeAndLockPages`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.
