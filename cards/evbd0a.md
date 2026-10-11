# `evbd0a.sys`

[Back to index](../README.md) · [Українська версія](evbd0a.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `53AF6CD54EAE4D4952BC1FA57225A6A376D27E61E7EEFD00ACAF6C1D9346BE0E` | `6F0FD28BB29F3519CC7EBDB10A4196ABCD935368` | `7F4B99B92E31D1B644503F85FEC13CB1` |

## Metadata

- **Filename:** `evbd0a.sys` (Identical copies: `evbd0a_1.sys`)
- **Size:** 3424160 bytes
- **Architecture:** 0x8664
- **Company:** QLogic Corporation
- **Product:** QLogic 10 GigE
- **Description:** QLogic 10 GigE VBD
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `physical memory mapping`, `section mapping (kernel R/W surface)`, `section object access`

**Imports:** `MmMapIoSpaceEx`, `ZwMapViewOfSection`, `ZwOpenSection`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.
