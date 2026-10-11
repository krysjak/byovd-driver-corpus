# `vmbusproxy.sys`

[Back to index](../README.md) · [Українська версія](vmbusproxy.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `10915CBC92DE7B95CCDC79CB6A9AA96B4F0190BC8B291F75FA47D78ABCADBDCA` | `7C9BC578F4CD789D2BF05F727B5EA1C2FF1BC988` | `0EB834AAE61D88250DC42F2BEAA9D973` |

## Metadata

- **Filename:** `vmbusproxy.sys`
- **Size:** 98304 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** Microsoft Hyper-V VMBus Proxy Driver
- **Signature:** unsigned
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `process address-space attach`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.
