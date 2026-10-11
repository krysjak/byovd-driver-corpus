# `IntelTACD.sys`

[Back to index](../README.md) · [Українська версія](IntelTACD.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `27E3DF3778E939D5FBFBC0428A6EF60516B7EAEB555ECC0A97833C7E37A09882` | `DE8FA9CF347EE6DCD5FC63EEEE359C35B42F7F03` | `22ECBDE59F8A5901D29BBBCB54979E7E` |

## Metadata

- **Filename:** `IntelTACD.sys`
- **Size:** 59952 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel Telemetry Aggregator Consumer Driver
- **Description:** Intel Telemetry Aggregator Consumer Driver 
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
