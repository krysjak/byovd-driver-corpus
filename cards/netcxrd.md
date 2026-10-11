# `netcxrd.sys`

[Back to index](../README.md) · [Українська версія](netcxrd.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `FD12CB90A7813BC4BDE0113AC9888014A2F05F8ED44FEA9A7769DDF203D5B04F` | `F5AD3B57A441AC73BF13044817E3A11936FCF676` | `EB8400DB8C49DF560A154E06BB4CFFB5` |

## Metadata

- **Filename:** `netcxrd.sys`
- **Size:** 294912 bytes
- **Architecture:** 0x8664
- **Company:** —
- **Product:** —
- **Description:** —
- **Signature:** unsigned
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `page locking`, `process address-space attach`, `process handle access`, `process termination`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmProbeAndLockPages`, `ZwOpenProcess`, `ZwTerminateProcess`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.
