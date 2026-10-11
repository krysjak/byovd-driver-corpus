# `e1dn.sys`

[Back to index](../README.md) · [Українська версія](e1dn.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `07A97BADAF775CEEC177F3B472AA6EEF878584B6A8CA5132EE3E36D4C5065EBA` | `EE759FB286CC673EACB77B8D719E24A04FD96E0E` | `71EA94952E2E21CD514A99FB86503F1F` |

## Metadata

- **Filename:** `e1dn.sys`
- **Size:** 1739360 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel(R) Ethernet Connection I219
- **Description:** Intel(R) Ethernet Controller (NetAdapterCx 2.2)
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
