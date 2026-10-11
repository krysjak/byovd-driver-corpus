# `amdacpksl_1.sys`

[Back to index](../README.md) · [Українська версія](amdacpksl_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `2E0EB25C34B68480AA161DD20C94FF5878C47526904CEDA2648CB1F09D2B517D` | `68ACBB86088ADAAB15FAE63F5C4DC0811076C47A` | `12301DA47DC0FB3651E7D3197E7F7ACE` |

## Metadata

- **Filename:** `amdacpksl_1.sys`
- **Size:** 353096 bytes
- **Architecture:** 0x8664
- **Company:** Advanced Micro Devices
- **Product:** AMD KSL Filter Driver
- **Description:** AMD KSL Filter Driver
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 55

## Capability profile

**Primitives:** `MDL allocation`, `page locking`, `physical address resolution`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmProbeAndLockPages`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.
