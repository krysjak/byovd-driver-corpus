# `Apfiltr.sys`

[Back to index](../README.md) · [Українська версія](Apfiltr.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `3E677EB99A4496443EE2CA4803C1115680F08FA548ADBBA45D9267D450A589B0` | `A4D9F13C9C785CEAB74228E61AEEF83395CBD52F` | `3F2DA60B4640D16872415448913B01C9` |

## Metadata

- **Filename:** `Apfiltr.sys`
- **Size:** 509696 bytes
- **Architecture:** 0x14c
- **Company:** Alps Electric Co., Ltd.
- **Product:** Alps Touch Pad Driver
- **Description:** Alps Touch Pad Driver
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 60

## Capability profile

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpace`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.
