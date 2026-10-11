# `MSIRCOMM.sys`

[Back to index](../README.md) · [Українська версія](MSIRCOMM.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `92BE91A71A23803E3136B3F32C9BE885718FD4663F48A1D1C676450F6EDE6926` | `CE65404A8387C1BAD1C0B331DA05C94360C022C7` | `61DF366F2D37F300C5D92861B03612F8` |

## Metadata

- **Filename:** `MSIRCOMM.sys`
- **Size:** 69632 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** Microsoft Infra-Red Communications Driver
- **Signature:** unsigned
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
