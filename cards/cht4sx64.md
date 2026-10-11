# `cht4sx64.sys`

[Back to index](../README.md) · [Українська версія](cht4sx64.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `FFAA9ABF91808E2569206A5A5D5D3542B02860965D8F1EA5790307648CD1E4D3` | `B35F32FD33B8B3D7F3ED58B7B856190A867C3DE6` | `ECB99F55AA110AC10B7D4795CB66464F` |

## Metadata

- **Filename:** `cht4sx64.sys` (Identical copies: `cht4sx64_1.sys`)
- **Size:** 320944 bytes
- **Architecture:** 0x8664
- **Company:** Chelsio Communications
- **Product:** Chelsio Communications iSCSI Controller
- **Description:** Chelsio iSCSI VMiniport Driver
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `section mapping (kernel R/W surface)`, `section object access`

**Imports:** `ZwMapViewOfSection`, `ZwOpenSection`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.
