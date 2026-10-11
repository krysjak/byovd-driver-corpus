# `hvservice_2.sys`

[Back to index](../README.md) · [Українська версія](hvservice_2.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `C9DF62EF78C6AD89C3200EB60244E5779E86BB8AD15B508024CB18FADFECD10D` | `8BF0EED14A88CDB52F1BF43C39AD472B38FD5B2A` | `5236C3E954FED48C0B0E429F2A0A9AD2` |

## Metadata

- **Filename:** `hvservice_2.sys` (Identical copies: `hvservice_3.sys`)
- **Size:** 103824 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** Hypervisor Boot Driver
- **Signature:** signed
- **Source:** `local`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** yes
- **On systems:** Live system
- **Score:** 75

## Capability profile

**Primitives:** `MDL allocation`, `process address-space attach`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.
