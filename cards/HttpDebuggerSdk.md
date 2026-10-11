# `HttpDebuggerSdk.sys`

[Back to index](../README.md) · [Українська версія](HttpDebuggerSdk.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `2E89606775ED719B9D950AE9D37E819A2567426FBE5C3E0AAD8D86FEC693B67B` | `5266036308E0D0EB837CC3126DBA5A0B6EC270FC` | `947C624C4BD48F8C66FCD00FC0F947D4` |

## Metadata

- **Filename:** `HttpDebuggerSdk.sys`
- **Size:** 100136 bytes
- **Architecture:** 0x8664
- **Company:** Windows (R) Win 7 DDK provider
- **Product:** Windows (R) Win 7 DDK driver
- **Description:** NetFilter SDK WFP Driver (WPP)
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `process lookup`

**Imports:** `IoAllocateMdl`, `PsLookupProcessByProcessId`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.
