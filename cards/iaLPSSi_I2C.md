# `iaLPSSi_I2C.sys`

[Back to index](../README.md) · [Українська версія](iaLPSSi_I2C.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `8445E41BAB21964C7F014742795E462BDDC6C37A261990B3D6BF4E637A719547` | `B226F7E4189BF32E6159BBF54C304753E6610633` | `EB82A11613326691508D9ED9A4FE29E7` |

## Metadata

- **Filename:** `iaLPSSi_I2C.sys` (Identical copies: `iaLPSSi_I2C_1.sys`)
- **Size:** 113152 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel(R) Serial IO Driver
- **Description:** Intel(R) Serial IO I2C Controller Driver
- **Signature:** unsigned
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `physical address resolution`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmMapIoSpace`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.
