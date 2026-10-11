# `iaLPSS2i_I2C_GLK.sys`

[Back to index](../README.md) · [Українська версія](iaLPSS2i_I2C_GLK.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `A92487129B81376471C842B9932FF3A7B3ABBBB89797978E3FDEAF71A6FD5E3F` | `7DAF5030A0444B5DD6101875CDCAAEB90509C3CB` | `2ED3B41C7CB4101ACB15D84D8AB5AA9D` |

## Metadata

- **Filename:** `iaLPSS2i_I2C_GLK.sys` (Identical copies: `iaLPSS2i_I2C_GLK_1.sys`)
- **Size:** 177664 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel(R) Serial IO Driver
- **Description:** Intel(R) Serial IO I2C Driver v2
- **Signature:** unsigned
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpaceEx`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.
