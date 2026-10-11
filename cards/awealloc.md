# `awealloc.sys`

[Back to index](../README.md) · [Українська версія](awealloc.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `5493A502F5ECE4F3FA5EAAC23C7D8E747535396835087E175041067B72607255` | `EF616F847E050C1C2F6EF6FF3C2A6B8E512A3AF6` | `4DB300DC68D6313671E122B3FC6B2411` |

## Metadata

- **Filename:** `awealloc.sys`
- **Size:** 36304 bytes
- **Architecture:** 0x8664
- **Company:** Olof Lagerkvist
- **Product:** imdisk
- **Description:** AWE Allocation Driver
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`

**Imports:** `IoAllocateMdl`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.
