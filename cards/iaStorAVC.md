# `iaStorAVC.sys`

[Back to index](../README.md) · [Українська версія](iaStorAVC.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `A46A34E6DC1573D29B87AD22B336C6A7358A657A416B1643C0D3DAD671D81692` | `AD6BE9C81E05628AF93FF3BA070EDCCE381F8422` | `76B3DFB22C302DBA9FA58C62D9668D04` |

## Metadata

- **Filename:** `iaStorAVC.sys` (Identical copies: `iaStorAVC_1.sys`)
- **Size:** 885568 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel(R) Rapid Storage Technology driver (inbox)
- **Description:** Intel(R) Rapid Storage Technology driver (inbox) - x64
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `physical address resolution`, `physical memory mapping`

**Imports:** `MmGetPhysicalAddress`, `MmMapIoSpace`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.
