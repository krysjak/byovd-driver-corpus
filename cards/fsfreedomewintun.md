# `fsfreedomewintun.sys`

[Back to index](../README.md) · [Українська версія](fsfreedomewintun.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `8C0487353F66F3DBC786A0AA05C0CB440DAAE4168AA77FBB08A512CC3783FBED` | `B89E19945E8C3160EB82A0CB7ED4D48C882DED2D` | `3A10D5E81FEE5AF6C10E17C9FA1714E5` |

## Metadata

- **Filename:** `fsfreedomewintun.sys` (Identical copies: `fsfreedomewintun_1.sys`)
- **Size:** 31248 bytes
- **Architecture:** 0x8664
- **Company:** F-Secure Corporation
- **Product:** F-Secure Freedome Wintun Driver
- **Description:** F-Secure Freedome Wintun Driver
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `page locking`, `process address-space attach`, `process lookup`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmProbeAndLockPages`, `PsLookupProcessByProcessId`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.
