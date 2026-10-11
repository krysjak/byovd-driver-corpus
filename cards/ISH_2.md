# `ISH_2.sys`

[Back to index](../README.md) · [Українська версія](ISH_2.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `8EAF758E6971DE895031F9857DA548B13999693A7BE5475C15CF66B4FAAB0F0E` | `86E14C97409C566C146750761295BA485F197679` | `58591E72C182B37FACD50238385EEC4A` |

## Metadata

- **Filename:** `ISH_2.sys`
- **Size:** 169648 bytes
- **Architecture:** 0x8664
- **Company:** Intel
- **Product:** ISS
- **Description:** Intel(R) Integrated Sensor Solution
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
