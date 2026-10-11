# `evbda.sys`

[Back to index](../README.md) · [Українська версія](evbda.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `60FE372E60F532099A242EF73C24C142CEB66CE7B1F7CA48B826A02D9DD513C9` | `D564E4461E032360D5CE57ADD1E1FE9A5E093940` | `12C40357B8103BF60F7485498C914CF3` |

## Metadata

- **Filename:** `evbda.sys` (Identical copies: `evbda_1.sys`)
- **Size:** 3441568 bytes
- **Architecture:** 0x8664
- **Company:** Marvell Semiconductor Inc.
- **Product:** QLogic 10 GigE
- **Description:** QLogic 10 GigE VBD
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpaceEx`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.
