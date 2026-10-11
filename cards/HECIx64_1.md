# `HECIx64_1.sys`

[Back to index](../README.md) · [Українська версія](HECIx64_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `2465DF47644BFEA249B2AD04F3443FD0494C82B5EAADB17E34325F989271EB1A` | `D776CB1C147CFACE2850336AADC0CD4129088164` | `E371FC5C4E76CE5313E68398F7950FB8` |

## Metadata

- **Filename:** `HECIx64_1.sys`
- **Size:** 64512 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel(R) Management Engine Interface
- **Description:** Intel(R) Management Engine Interface
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 80

## Capability profile

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpace`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.
