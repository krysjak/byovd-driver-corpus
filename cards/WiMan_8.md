# `WiMan_8.sys`

[Back to index](../README.md) · [Українська версія](WiMan_8.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `C29958A329A309435D910C9116081DBA5834BD13594B99D324F6EAF73B1623DF` | `D28D86C269D29581E774ED0DFD8FFCD88F64404A` | `1BA24C04F2139FE7C402196BFE8E9C8A` |

## Metadata

- **Filename:** `WiMan_8.sys`
- **Size:** 152360 bytes
- **Architecture:** 0x8664
- **Company:** —
- **Product:** —
- **Description:** —
- **Signature:** signed
- **Source:** `oem:hp`
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
