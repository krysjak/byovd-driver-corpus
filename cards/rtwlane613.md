# `rtwlane613.sys`

[Back to index](../README.md) · [Українська версія](rtwlane613.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `021EDBDD44F9E208AB343F24F467BBC3EFA02E0CC2FF727179488BFAD2F2F481` | `25FEFF9E5CF6E8775B6301B0758706FDB7E7EDEC` | `103B13C00B0CDF1853E786A21B2F7A81` |

## Metadata

- **Filename:** `rtwlane613.sys`
- **Size:** 18363024 bytes
- **Architecture:** 0x8664
- **Company:** Realtek Semiconductor Corporation                           
- **Product:** Realtek  PCIEWireless LAN PCI-E NIC                                     
- **Description:** Realtek PCIE NDIS Driver 239ddee
- **Signature:** signed
- **Source:** `oem:hp`
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
