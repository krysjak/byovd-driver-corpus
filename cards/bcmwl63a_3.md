# `bcmwl63a_3.sys`

[Back to index](../README.md) · [Українська версія](bcmwl63a_3.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `8FA00E445D7C5A1C38064B461CBBA047F4E854A43F55E5197DEFDA48AECD01F5` | `2D9FA5CC2613020091D5F9598677147E13156684` | `1D993452E89B23F1D1DFF4ECD7223BCA` |

## Metadata

- **Filename:** `bcmwl63a_3.sys`
- **Size:** 7515312 bytes
- **Architecture:** 0x8664
- **Company:** Broadcom Corporation
- **Product:** Broadcom 802.11 Network Adapter wireless driver
- **Description:** Broadcom 802.11 Network Adapter wireless driver
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 75

## Capability profile

**Primitives:** `physical address resolution`, `physical memory mapping`

**Imports:** `MmGetPhysicalAddress`, `MmMapIoSpace`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.
