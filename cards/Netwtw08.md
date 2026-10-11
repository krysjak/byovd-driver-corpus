# `Netwtw08.sys`

[Back to index](../README.md) · [Українська версія](Netwtw08.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `18E1A3736F2D1ECCE196C008A474ABBB430B3F1310C731D5B58D9E9F13DE90B3` | `314EF12EDD6174D1D319DAB39AB7B6BBD88F008F` | `61A41DBA0D1D6159AB8BF7C0B952B064` |

## Metadata

- **Filename:** `Netwtw08.sys`
- **Size:** 8815104 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel® Wireless WiFi Link Adapter
- **Description:** Intel® Wireless WiFi Link Driver
- **Signature:** unsigned
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `physical address resolution`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmMapIoSpace`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.
