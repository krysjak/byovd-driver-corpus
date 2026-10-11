# `iai2c.sys`

[Back to index](../README.md) · [Українська версія](iai2c.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `9296A14590DFD94A3C728CAF3CA91BA211F27974F9CFF8417CDDC00D1453315C` | `458A43F7F0674B68504AF1D02EA33F2F6FD5A03F` | `48EDB9B5DAB7D294951A520330F13715` |

## Metadata

- **Filename:** `iai2c.sys` (Identical copies: `iai2c_1.sys`)
- **Size:** 91136 bytes
- **Architecture:** 0x8664
- **Company:** Intel(R) Corporation
- **Product:** Intel(R) Serial IO I2C Driver
- **Description:** Intel(R) Serial IO I2C Driver
- **Signature:** unsigned
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmMapIoSpaceEx`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.
