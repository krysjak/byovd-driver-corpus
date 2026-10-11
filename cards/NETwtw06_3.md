# `NETwtw06_3.sys`

[Back to index](../README.md) · [Українська версія](NETwtw06_3.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `41A7819D6BA1FE9A92612A85E112DF6F565B2D61B529A0E15F85F880174C9470` | `E1BED75C5E7ACCD87E99F74AFCD832942FEB89EA` | `CA50241E1E5E21178C15EEF4519AB09C` |

## Metadata

- **Filename:** `NETwtw06_3.sys`
- **Size:** 8899176 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel® Wireless WiFi Link Adapter
- **Description:** Intel® Wireless WiFi Link Driver
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 60

## Capability profile

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpace`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.
