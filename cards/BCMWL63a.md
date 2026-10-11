# `BCMWL63a.SYS`

[Back to index](../README.md) · [Українська версія](BCMWL63a.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `64CBE1AA061F0CC761A6D9E3C0E4C484EE09CACA932CB18D1947BC7D9F893BA3` | `E8BD3E75168E54BCBA3CDC89845722C3DCAF0CEE` | `E6618C2CAEEE8A2644FD46B98304954A` |

## Metadata

- **Filename:** `BCMWL63a.SYS`
- **Size:** 7585280 bytes
- **Architecture:** 0x8664
- **Company:** Broadcom Corporation
- **Product:** Broadcom 802.11 Network Adapter wireless driver
- **Description:** Broadcom 802.11 Network Adapter wireless driver
- **Signature:** unsigned
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
