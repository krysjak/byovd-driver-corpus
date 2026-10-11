# `gna_1.sys`

[Back to index](../README.md) · [Українська версія](gna_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `BF0816E1BC5561094E3E4B2F27859AEA4D655F1546E9193100DE9A8A4D4C14D3` | `025F3C681BC99DBF9B19ED6E7419383015787013` | `6EA3A12F265CB170FF3ED395AB507181` |

## Metadata

- **Filename:** `gna_1.sys`
- **Size:** 88776 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel (R) Gaussian & Neural Accelerator
- **Description:** Intel (R) GNA device driver (10.64.2.19041)
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** —
- **On systems:** OEM package
- **Score:** 65

## Capability profile

**Primitives:** `MDL allocation`, `page locking`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmMapIoSpaceEx`, `MmProbeAndLockPages`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.
