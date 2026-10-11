# `Usb4HostRouter_1.sys`

[Back to index](../README.md) · [Українська версія](Usb4HostRouter_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `60545983B8A91834043F17C9F8634FE51032E144CBE8C94D67C5809C7272A331` | `2125990B432F348D54BA4D7629101E105413076E` | `07DB3961F031524FC737695535E6ED69` |

## Metadata

- **Filename:** `Usb4HostRouter_1.sys` (Identical copies: `Usb4HostRouter_2.sys`)
- **Size:** 1168792 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** USB4(TM) Host Router Driver
- **Signature:** signed
- **Source:** `local`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Live system
- **Score:** 60

## Capability profile

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpaceEx`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.
