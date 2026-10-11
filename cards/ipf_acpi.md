# `ipf_acpi.sys`

[Back to index](../README.md) · [Українська версія](ipf_acpi.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `7C6F0BD4E7F68BF5130805BADD3C8703B7D95BA40D3D464A473C3C776996B8C4` | `5A6ADE3FC537B20FCA0501E6FBC4A9232937A5EA` | `3638B312FC8CBCA5E34B7C16CF131F66` |

## Metadata

- **Filename:** `ipf_acpi.sys`
- **Size:** 90184 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel(R) Innovation Platform Framework
- **Description:** Intel(R) Innovation Platform Framework ACPI Participant
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 60

## Capability profile

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpace`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.
