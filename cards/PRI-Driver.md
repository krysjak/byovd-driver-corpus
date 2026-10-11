# `PRI-Driver.sys`

[Back to index](../README.md) · [Українська версія](PRI-Driver.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `FEA19D478F7FE6DC5109ABA767C1B952F389159E98456BB0046F785AB3FF476C` | `CF82BCE42ACD57A7F8FF1FB1C3962D7D35352C39` | `0E6B8871764BAAF082B36C4BF101B869` |

## Metadata

- **Filename:** `PRI-Driver.sys`
- **Size:** 378000 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel(R) Platform Register Interface Driver
- **Description:** Intel(R) Platform Register Interface Driver 
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 60

## Capability profile

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpace`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.
