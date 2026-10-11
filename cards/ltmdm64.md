# `ltmdm64.sys`

[Back to index](../README.md) · [Українська версія](ltmdm64.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `570195A36BB5162D59516708C92E8BF7A558A4B05ADCE30A624C805541962131` | `6AD83D856585C15A51C75DD2DE6E4B334F94316D` | `CC5CF4BDAA6671E4F72B1B37E0A2DB4A` |

## Metadata

- **Filename:** `ltmdm64.sys`
- **Size:** 543744 bytes
- **Architecture:** 0x8664
- **Company:** Agere Systems
- **Product:** Agere V.92 Data+Fax Modem Version 8.36
- **Description:** Agere Windows Modem
- **Signature:** unsigned
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpace`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.
