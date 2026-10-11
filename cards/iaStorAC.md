# `iaStorAC.sys`

[Back to index](../README.md) · [Українська версія](iaStorAC.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `0DC0471FC9CD6029188579A6A81AE3C39228EC555F209A5F837548269B93893B` | `9D7B142F2EB7C7AAB9F441FFCB0F705887547CA3` | `7B5C66F6ED486974A7D0FF68E03C6CC5` |

## Metadata

- **Filename:** `iaStorAC.sys`
- **Size:** 1545424 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel(R) Rapid Storage Technology driver 
- **Description:** Intel(R) Rapid Storage Technology driver - x64
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 75

## Capability profile

**Primitives:** `physical address resolution`, `physical memory mapping`

**Imports:** `MmGetPhysicalAddress`, `MmMapIoSpace`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.
