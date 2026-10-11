# `qcwlan64_1.sys`

[Back to index](../README.md) · [Українська версія](qcwlan64_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `D02783837B43C543EC84F7391A6D25D05D3573DC78A005629059A0B1AB9DF04F` | `5C983AEBEC35526F440D7363B477A65D06C11EBD` | `DA0C0ADADA63333D2BBB4A14F9AEA34F` |

## Metadata

- **Filename:** `qcwlan64_1.sys`
- **Size:** 3150168 bytes
- **Architecture:** 0x8664
- **Company:** Qualcomm Atheros, Inc.
- **Product:** Driver for Qualcomm Atheros QCA61x4/QCA9377 Network Adapter
- **Description:** Qualcomm Atheros Extensible Wireless LAN device driver
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** —
- **On systems:** OEM package
- **Score:** 70

## Capability profile

**Primitives:** `MDL allocation`, `physical address resolution`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmMapIoSpace`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.
