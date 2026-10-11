# `iaLPSS2_UART2_MTL.sys`

[Back to index](../README.md) · [Українська версія](iaLPSS2_UART2_MTL.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `74C72D631D98F9ACA9C9459F411DC5E5F129BF64CFABE3CDBEFA0E7E17551C70` | `58B393B5A65DE6434E9E62D8DA8C0EF9ECC90994` | `4D5098ADFBBA2C92DD1CFA58EBE012C0` |

## Metadata

- **Filename:** `iaLPSS2_UART2_MTL.sys`
- **Size:** 322560 bytes
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
