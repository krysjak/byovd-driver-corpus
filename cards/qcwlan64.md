# `qcwlan64.sys`

[Back to index](../README.md) · [Українська версія](qcwlan64.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `428B90EC39DADF75041C3926990457CBAC46F3CFB2DE9833395FAE56C45657D0` | `C8592A86C2922A330A1BFED9F639078D9990D91F` | `7DEBC94DEA39D103477AC2A89AE6302C` |

## Metadata

- **Filename:** `qcwlan64.sys`
- **Size:** 2706944 bytes
- **Architecture:** 0x8664
- **Company:** Qualcomm Atheros, Inc.
- **Product:** Driver for Qualcomm Atheros QCA61x4/QCA9377 Network Adapter
- **Description:** Qualcomm Atheros Extensible Wireless LAN device driver
- **Signature:** unsigned
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** —
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `physical address resolution`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmMapIoSpace`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.
