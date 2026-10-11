# `expressvpn-tun.sys`

[Back to index](../README.md) · [Українська версія](expressvpn-tun.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `784D93A908D9E543272072D49DC4224D09DB2052983E66BDE32E4AF6921DAD9F` | `DB28B6C763110095FDA71925053DAD5317141CF3` | `4E72AE539702BF5A979B8B382D7F8027` |

## Metadata

- **Filename:** `expressvpn-tun.sys` (Identical copies: `expressvpn-tun_1.sys`)
- **Size:** 41976 bytes
- **Architecture:** 0x8664
- **Company:** ExpressVPN
- **Product:** ExpressVPN Wintun Driver
- **Description:** ExpressVPN Wintun Driver
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
