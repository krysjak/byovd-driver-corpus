# `iaStorVD_3.sys`

[Back to index](../README.md) · [Українська версія](iaStorVD_3.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `5C2AF187D0E32380B9AE552DD94AC8B788D346889A21D2EE0C9D1DB64690F4CE` | `A00E888B7D48C3BC50F2505A4BCF7142C41748B3` | `688BDC09B13B3F4C0462E3AEB568E713` |

## Metadata

- **Filename:** `iaStorVD_3.sys`
- **Size:** 1605296 bytes
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
