# `VSTAZL6.SYS`

[Back to index](../README.md) · [Українська версія](VSTAZL6.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `63376322BFFAFF2F166AF3FDD3F1A346C21FAE21F406F659F8630779D1D6525D` | `E3DCA8F5408291D57AE5A5AAF565DCD8E237B38E` | `0C4540311E11664B245A263E1154CEF8` |

## Metadata

- **Filename:** `VSTAZL6.SYS`
- **Size:** 292864 bytes
- **Architecture:** 0x8664
- **Company:** Conexant Systems, Inc.
- **Product:** SoftK56 Modem Driver
- **Description:** HSF_HWAZL WDM driver
- **Signature:** unsigned
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`

**Imports:** `IoAllocateMdl`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.
