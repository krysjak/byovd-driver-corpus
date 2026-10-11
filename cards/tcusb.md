# `tcusb.sys`

[Back to index](../README.md) · [Українська версія](tcusb.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `6AF2AEB769BD5903DA8FB6E75598C8E22A3091F4B3B8981003EC247BF3B07652` | `87A826C53DC7ACD9DEE474FBE2790D8B7DFCD208` | `C0EB9CC6E12B29CDA16DB8A200BA4765` |

## Metadata

- **Filename:** `tcusb.sys`
- **Size:** 51816 bytes
- **Architecture:** 0x14c
- **Company:** AuthenTec, Inc.
- **Product:** TouchChip USB Kernel Driver
- **Description:** TouchChip USB Kernel Driver
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 70

## Capability profile

**Primitives:** `MDL allocation`, `page locking`

**Imports:** `IoAllocateMdl`, `MmProbeAndLockPages`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.
