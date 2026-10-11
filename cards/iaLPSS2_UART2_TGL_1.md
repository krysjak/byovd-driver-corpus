# `iaLPSS2_UART2_TGL_1.sys`

[Back to index](../README.md) · [Українська версія](iaLPSS2_UART2_TGL_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `712666D0AE0005989477913CE6E5A1DEF244F679797B87460C99679B26FBB86A` | `A85DD14CBEF181B925F0F4E2A5024EBC9BD12D01` | `9F9AE835529EBFB9ADE402E51EE62134` |

## Metadata

- **Filename:** `iaLPSS2_UART2_TGL_1.sys`
- **Size:** 313504 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel(R) Serial IO Driver
- **Description:** Intel(R) Serial IO UART Driver
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 60

## Capability profile

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpaceEx`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.
