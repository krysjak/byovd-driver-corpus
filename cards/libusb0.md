# `libusb0.sys`

[Back to index](../README.md) · [Українська версія](libusb0.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `8058F2AFE6EF96A7D2DED432997FD8655970C9EA75A938EE4557D6A2CB4CC989` | `81D2B572EC0D24ABA11ED6BFA9174FFAD54140B7` | `16E18CED459B1824234890386EE66CD5` |

## Metadata

- **Filename:** `libusb0.sys`
- **Size:** 52832 bytes
- **Architecture:** 0x8664
- **Company:** http://libusb-win32.sourceforge.net
- **Product:** LibUSB-Win32 - Kernel Driver
- **Description:** LibUSB-Win32 - Kernel Driver
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`

**Imports:** `IoAllocateMdl`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.
