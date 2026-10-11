# `droidcamvideo.sys`

[Back to index](../README.md) · [Українська версія](droidcamvideo.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `5772C8D9459A1B05699ED7591EED7A9AEA8D5F4F35B01666D198893B79E0C959` | `953D73C0E89FEAB03D8C98BA6F58BFAC187FA2B7` | `F0357B94DDE14DC16C759AC7EB240CE5` |

## Metadata

- **Filename:** `droidcamvideo.sys`
- **Size:** 136360 bytes
- **Architecture:** 0x8664
- **Company:** Windows (R) Win 7 DDK provider
- **Product:** DroidCam
- **Description:** Virtual Video Driver
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `page locking`, `section mapping (kernel R/W surface)`, `section object access`

**Imports:** `IoAllocateMdl`, `MmProbeAndLockPages`, `ZwMapViewOfSection`, `ZwOpenSection`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.
