# `WiMan_2.sys`

[Back to index](../README.md) · [Українська версія](WiMan_2.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `A885C2557F1243CA7AF6A40D391CD327BC38C1DE8F876ADF6AB57F8CD982FC77` | `78CC91CB5E865C6FF9C6667217B5D849CAED7FAA` | `88775A02898BE551A385496B877A79F7` |

## Metadata

- **Filename:** `WiMan_2.sys`
- **Size:** 171936 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel® Wireless Manageability
- **Description:** Intel® Wireless Manageability
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 85

## Capability profile

**Primitives:** `MDL allocation`, `physical address resolution`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmMapIoSpaceEx`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.
