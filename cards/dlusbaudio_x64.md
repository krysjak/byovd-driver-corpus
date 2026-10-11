# `dlusbaudio_x64.sys`

[Back to index](../README.md) · [Українська версія](dlusbaudio_x64.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `EB6674CAD3282E2A520AB55A28B0A38A59B3D3DCC16088D58FA4A807F404E986` | `1259B6E10E1C7F539ECD655E872342C11303AD52` | `36AB6683C7490748E4E6C1ABC19EF802` |

## Metadata

- **Filename:** `dlusbaudio_x64.sys`
- **Size:** 237784 bytes
- **Architecture:** 0x8664
- **Company:** DisplayLink Corp.
- **Product:** DisplayLink USB Audio 2.0 Class Driver
- **Description:** DisplayLink USB Audio Driver
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
