# `e2fn.sys`

[Back to index](../README.md) · [Українська версія](e2fn.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `545B4BAD3CB0A02A4FEAE77480F0447B33F0A3F858DBDDE84C282F77DF898078` | `569346BB5B14A837AAEE4C986E899FF3A7D53207` | `10E353864C680ED0F688666442E3FDC7` |

## Metadata

- **Filename:** `e2fn.sys`
- **Size:** 1427528 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel(R) Ethernet Controller I225
- **Description:** Intel(R) Ethernet Controller (NetAdapterCx 2.2)
- **Signature:** signed
- **Source:** `oem:hp`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 60

## Capability profile

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpaceEx`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.
