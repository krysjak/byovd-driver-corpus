# `ibtpci_1.sys`

[Back to index](../README.md) · [Українська версія](ibtpci_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `4EAC78D9D64F0A358C069A907966530799CCF2A4B6A7585A1B2EB3EE3F760CBF` | `6070F809453A7C29257C0549E176E4FCFCE10918` | `4497A04A809E3B5998ECDF2AE970F392` |

## Metadata

- **Filename:** `ibtpci_1.sys`
- **Size:** 7831480 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel(R) Wireless Bluetooth(R)
- **Description:** Intel(R) Wireless Bluetooth(R) PCIe Function Driver
- **Signature:** signed
- **Source:** `oem:dell`
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
