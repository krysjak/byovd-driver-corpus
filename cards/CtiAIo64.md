# `CtiAIo64.sys`

[Back to index](../README.md) · [Українська версія](CtiAIo64.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `90B1422B71BAF1AD713DBF7D5E74B566622DEFF44451F7E69667562D3E221A45` | `4BECA13D2AE4EC99764D46432EF59554569882DC` | `58E831247EF3772F3D7AC0B630B9EB00` |

## Metadata

- **Filename:** `CtiAIo64.sys`
- **Size:** 39672 bytes
- **Architecture:** 0x8664
- **Company:** Creative Technology Innovation Co., LTd.
- **Product:** CtiAIo64 Driver Version 1.1
- **Description:** CTIA IO driver
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** —
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `section mapping (kernel R/W surface)`, `section object access`

**Imports:** `ZwMapViewOfSection`, `ZwOpenSection`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.
