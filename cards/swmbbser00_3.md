# `swmbbser00_3.sys`

[Back to index](../README.md) · [Українська версія](swmbbser00_3.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `48A16151E5750E1B6AFA669AFE80352B482A83267E90FD9E00F92FF9786F66E3` | `000829D12E4159A17770EB736303680D1EB04D29` | `D48D3EE57ED6D258631B08861E2139B7` |

## Metadata

- **Filename:** `swmbbser00_3.sys`
- **Size:** 245616 bytes
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
