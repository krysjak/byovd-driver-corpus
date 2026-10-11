# `Classpnp.sys`

[Back to index](../README.md) · [Українська версія](Classpnp.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `D20BABA4F0D709893F30E212DF4E15F224F84B7E1AE08F4BE734660107BB2732` | `78E6F5E0B00816AC23966FF41EB4CEF4EBCFC06C` | `E7D810658448A05AAF91700A236B186F` |

## Metadata

- **Filename:** `Classpnp.sys`
- **Size:** 505304 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** SCSI Class System Dll
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `page locking`

**Imports:** `IoAllocateMdl`, `MmProbeAndLockPages`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.
