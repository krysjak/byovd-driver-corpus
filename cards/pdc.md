# `pdc.sys`

[Back to index](../README.md) · [Українська версія](pdc.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `83487A10400C635328957D47A5F43540E971C9328A83D46455391AF3A5C6838C` | `4A2BF68DAD8F79071A84ED1AC74EF725628F9DD3` | `CFE716E7843009AE733BFE3748C0651C` |

## Metadata

- **Filename:** `pdc.sys`
- **Size:** 214504 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** Power Dependency Coordinator Driver
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `process address-space attach`, `process handle access`, `process lookup`

**Imports:** `KeStackAttachProcess`, `PsLookupProcessByProcessId`, `ZwOpenProcess`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.
