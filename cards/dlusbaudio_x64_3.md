# `dlusbaudio_x64_3.sys`

[Back to index](../README.md) · [Українська версія](dlusbaudio_x64_3.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `62713897D8495F648061CED38D89FC887284960E2877CAF69FE5DA336F84366E` | `AD76F565F8C555B46DF19EDC9FBA9FA22256C8DB` | `40DABA8F68FF6F174C797E4869E7923E` |

## Metadata

- **Filename:** `dlusbaudio_x64_3.sys`
- **Size:** 229704 bytes
- **Architecture:** 0x8664
- **Company:** DisplayLink Corp.
- **Product:** DisplayLink USB Audio 2.0 Class Driver
- **Description:** DisplayLink USB Audio Driver
- **Signature:** signed
- **Source:** `oem:hp`
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
