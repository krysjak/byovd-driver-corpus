# `snxpserx.sys`

[Back to index](../README.md) · [Українська версія](snxpserx.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `3C75C74BD1929CB4D1E589C9FC7228224C5FDAE835610CB8AA53BDD3CBAE9AC7` | `AB07B6B292E32E59E67B60842E1AB14ABEF623F8` | `58BC27E1765EFC90ACB0413C4F08306D` |

## Metadata

- **Filename:** `snxpserx.sys`
- **Size:** 93088 bytes
- **Architecture:** 0x14c
- **Company:** SUNIX Co., Ltd.
- **Product:** SUNIX Multi I/O Card
- **Description:** SUNIX Serial Driver (x86)
- **Signature:** signed
- **Source:** `oem:hp`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 90

## Capability profile

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpace`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.
