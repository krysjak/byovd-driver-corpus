# `npcap.sys`

[Back to index](../README.md) · [Українська версія](npcap.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `414D458317078EDD58CBF662A6464E659C403991309BD5648A8040F75A4D7D8F` | `7D272BDAF7CEC7A78E3F783EB25845151A65A825` | `F84BF1529FFE88E3CCA8220B9A8CE313` |

## Metadata

- **Filename:** `npcap.sys` (Identical copies: `npcap_1.sys`)
- **Size:** 80456 bytes
- **Architecture:** 0x8664
- **Company:** Nmap Software LLC
- **Product:** Npcap
- **Description:** npcap.sys (NT6 AMD64) Kernel Filter Driver
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`

**Imports:** `IoAllocateMdl`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.
