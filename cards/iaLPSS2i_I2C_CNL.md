# `iaLPSS2i_I2C_CNL.sys`

[Back to index](../README.md) · [Українська версія](iaLPSS2i_I2C_CNL.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `F105EDD16E38F5C0044CC7139E4084A04B0AE3212171A1C7F6FE759F3F5F77FC` | `2D48737FB6DC8ED9B6D50FB06867E91C72DC50F9` | `897478D8FACEAE8681F6F3502201EC68` |

## Metadata

- **Filename:** `iaLPSS2i_I2C_CNL.sys` (Identical copies: `iaLPSS2i_I2C_CNL_1.sys`)
- **Size:** 177152 bytes
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
