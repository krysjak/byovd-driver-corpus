# `ibtpci.sys`

[Back to index](../README.md) · [Українська версія](ibtpci.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `F039D02E63B0E46A64E30A9B9F83D96913B456FDC90DC802A15366D69715A4A7` | `EF4A410B0643143F9B593ECC285C2C7DA11CB23D` | `1A04E3529586A6674975FD7396B773CD` |

## Metadata

- **Filename:** `ibtpci.sys`
- **Size:** 19637144 bytes
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
