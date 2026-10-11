# `Netwtw04.sys`

[Back to index](../README.md) · [Українська версія](Netwtw04.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `317C8979221D4797D04FD160FC9BDD2783044DCE34D66D0DF0290A24A2ADAB89` | `4CAD743FE0F50A84BD3513F398EE6299B47D553E` | `E51C665DB70389EF5FE48F8D040894C0` |

## Metadata

- **Filename:** `Netwtw04.sys`
- **Size:** 8695808 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel® Wireless WiFi Link Adapter
- **Description:** Intel® Wireless WiFi Link Driver
- **Signature:** unsigned
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpace`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.
