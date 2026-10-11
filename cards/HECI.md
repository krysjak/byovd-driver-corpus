# `HECI.sys`

[Back to index](../README.md) · [Українська версія](HECI.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `FECC0A73FCD9EAA124FA2EF3A2B73CD5069B22F80A5E275CF2FE943F38F7405E` | `BF1B57B438CD06C750C91E1AA72D20C8F481F1AA` | `6C87E806EDE05928EDA5E6BCB426BB7D` |

## Metadata

- **Filename:** `HECI.sys`
- **Size:** 56280 bytes
- **Architecture:** 0x14c
- **Company:** Intel Corporation
- **Product:** Intel(R) Management Engine Interface
- **Description:** Intel(R) Management Engine Interface
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
