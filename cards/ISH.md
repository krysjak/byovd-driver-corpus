# `ISH.sys`

[Back to index](../README.md) · [Українська версія](ISH.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `2BA8B6FD6A3A6EE1B2A30E960CD5F92A8985172B63C0A38EA2EF2154C8FD5A6C` | `9D07CDF43F4EAD35385A22058313154CE17EAE4E` | `DA6DEE41B0DEEAF086E43D9D2B5DEDD2` |

## Metadata

- **Filename:** `ISH.sys`
- **Size:** 167072 bytes
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
