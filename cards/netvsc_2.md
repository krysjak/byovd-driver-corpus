# `netvsc_2.sys`

[Back to index](../README.md) · [Українська версія](netvsc_2.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `6DE23BFD7C244E7B25040675BBF187E132EE030558B0AA91974B6EA4C2606940` | `689BBC02DD9D96D68ABFDAC05DAAFEFE4547886A` | `CC308EDAFDF5BED513BFF64C9E738126` |

## Metadata

- **Filename:** `netvsc_2.sys` (Identical copies: `netvsc_3.sys`)
- **Size:** 398744 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** Virtual NDIS Miniport
- **Signature:** signed
- **Source:** `local`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Live system
- **Score:** 70

## Capability profile

**Primitives:** `MDL allocation`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmMapIoSpaceEx`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.
