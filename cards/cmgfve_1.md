# `cmgfve_1.sys`

[Back to index](../README.md) · [Українська версія](cmgfve_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `818C6FAC8EA1CD24388EA34FE4BB8E4DE60A4B2471DCA4C565F9F3A82582D631` | `65DE14C8953E9D47C3D51993EC2A62573C5473B5` | `69BC760DA2EFE514CC1042B3B5C38224` |

## Metadata

- **Filename:** `cmgfve_1.sys`
- **Size:** 210656 bytes
- **Architecture:** 0x8664
- **Company:** Dell Inc.
- **Product:** CmgFVE.sys (64b,rls)
- **Description:** Credant Full Volume Encryption Driver
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 90

## Capability profile

**Primitives:** `MDL allocation`, `contiguous physical allocation`, `page locking`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmAllocateContiguousMemory`, `MmMapIoSpace`, `MmProbeAndLockPages`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.
