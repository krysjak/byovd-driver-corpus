# `WwanNet.sys`

[Back to index](../README.md) · [Українська версія](WwanNet.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `84954F363E456659289559744AEFA4D50C1B896C983F31BE3B478968C6B3D9D4` | `9D66D325135AF3003CDC6AD3687D11FA9C0C5C15` | `47A9D3A60B2F0D135A7E6F6D1A8DEAFB` |

## Metadata

- **Filename:** `WwanNet.sys`
- **Size:** 459320 bytes
- **Architecture:** 0x8664
- **Company:** Fibocom Wireless Inc.
- **Product:** Fibocom Wwan 5G NetAdapter Stack
- **Description:** Fibocom Wwan NetAdapter Mbb-Client Driver"
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 85

## Capability profile

**Primitives:** `contiguous physical allocation`, `physical address resolution`, `physical memory mapping`

**Imports:** `MmAllocateContiguousMemory`, `MmGetPhysicalAddress`, `MmMapIoSpaceEx`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.
