# `droidcamaudio.sys`

[Back to index](../README.md) · [Українська версія](droidcamaudio.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `AD10D5D6F5CA02A114FC2890C9D5B8A595B8E244CCB89810304788A34B57C49A` | `49E3963ADD926E0962DAAD373AEAECAF36738E12` | `1E948F1455E3467D5B83A547FCEC093D` |

## Metadata

- **Filename:** `droidcamaudio.sys`
- **Size:** 33808 bytes
- **Architecture:** 0x8664
- **Company:** Windows (R) Win 7 DDK provider
- **Product:** DroidCam
- **Description:** Virtual Audio Driver
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
