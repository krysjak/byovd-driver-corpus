# `Netwtw02.sys`

[Back to index](../README.md) · [Українська версія](Netwtw02.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `24D33FB3DDD889157C606EEDE21CE943A90C658F1AC7BB596F031AA9409D92B3` | `2AD2E933A2642E5D0FCDCACF1AB9D4AEB1574B26` | `F4D84DDD179F8AE0A10016BDDDB8DAA2` |

## Metadata

- **Filename:** `Netwtw02.sys`
- **Size:** 6715904 bytes
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
