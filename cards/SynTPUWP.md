# `SynTPUWP.sys`

[Back to index](../README.md) · [Українська версія](SynTPUWP.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `BA51CDEF49BED797A36ECC5AD41EBCD792B9AB1F86D810350016B5A4C5ADA48C` | `6A3D2F86756EEA65C4EB49092AB7728A7D611162` | `76494BC6DEF95C308CF62EA9311BE774` |

## Metadata

- **Filename:** `SynTPUWP.sys`
- **Size:** 752984 bytes
- **Architecture:** 0x8664
- **Company:** Synaptics Incorporated
- **Product:** Synaptics Pointing Device Driver
- **Description:** Synaptics Touchpad Win64 Driver
- **Signature:** signed
- **Source:** `oem:hp`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 70

## Capability profile

**Primitives:** `MDL allocation`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmMapIoSpace`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.
