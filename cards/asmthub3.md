# `asmthub3.sys`

[Back to index](../README.md) · [Українська версія](asmthub3.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `C87A5C6C808E1FD7E4ED0AF6EE9FF64A70D1D6F9C951966E2A2EA49F41C456D3` | `1B0AC225AAF4E69F5AB679DB4BAA5D6FB352C88B` | `DB5B39DFDE775F792B2E28E7B6B9CD9A` |

## Metadata

- **Filename:** `asmthub3.sys`
- **Size:** 160936 bytes
- **Architecture:** 0x8664
- **Company:** ASMedia Technology Inc
- **Product:** ASMedia USB 3.1 Host Drivers
- **Description:** ASMedia USB3 Hub Driver
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 60

## Capability profile

**Primitives:** `MDL allocation`

**Imports:** `IoAllocateMdl`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.
