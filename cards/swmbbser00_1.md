# `swmbbser00_1.sys`

[Back to index](../README.md) · [Українська версія](swmbbser00_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `F91E42888AFC9F3CFA501C13472F6D1C4973BBCD12BFE7139F6A81D90F7473A4` | `AF3EB1FCEB7713B173B7CD53AFF8B814D8CF2343` | `CBB700BA37F2DE383CD22B29607748FF` |

## Metadata

- **Filename:** `swmbbser00_1.sys`
- **Size:** 245328 bytes
- **Architecture:** 0x14c
- **Company:** Sierra Wireless Incorporated
- **Product:** Sierra Wireless Incorporated USB Modem/Serial Device Driver
- **Description:** USB Modem/Serial Device Driver
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 80

## Capability profile

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpace`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.
