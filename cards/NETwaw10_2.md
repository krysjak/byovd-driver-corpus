# `NETwaw10_2.sys`

[Back to index](../README.md) · [Українська версія](NETwaw10_2.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `D821F2A91F8AFA523EA4A98632CF23331552807881F89024D6A0B86977F6497E` | `27DA15C87BF783FD7B95FF75A51A2B0EEA593C5D` | `681775933DB3765754F74E5CC5702FC6` |

## Metadata

- **Filename:** `NETwaw10_2.sys`
- **Size:** 4889168 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel® Wireless WiFi Link Adapter
- **Description:** R Intel Wireless WiFi Link Driver
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
