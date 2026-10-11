# `TbtBusDrv_4.sys`

[Back to index](../README.md) · [Українська версія](TbtBusDrv_4.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `6127D33E6CA8A104F646EAD60ED95EEE482FD082156FC746D6DC9D18E7D57588` | `CABE068F36C44191EDFEC5833C60D2F89AC1B4B3` | `5471075EB777F38C49E8E39D2E675BE2` |

## Metadata

- **Filename:** `TbtBusDrv_4.sys`
- **Size:** 2141456 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Thunderbolt(TM) Bus Driver
- **Description:** Thunderbolt(TM) Bus Driver
- **Signature:** signed
- **Source:** `oem:hp`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 60

## Capability profile

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpaceEx`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.
