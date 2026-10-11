# `iaStorVD_4.sys`

[Back to index](../README.md) · [Українська версія](iaStorVD_4.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `3DF428F5DCA091BD58CDDB05FD4EBCE45E68D9B013242F7A0C4B8B94BDE1E2FD` | `213289BDB02C50C63A46DBB8A21487C04BECF6A1` | `453ECC094388E89AD431A2A1E4D92D1D` |

## Metadata

- **Filename:** `iaStorVD_4.sys`
- **Size:** 1587376 bytes
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
