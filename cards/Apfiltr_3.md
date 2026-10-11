# `Apfiltr_3.sys`

[Back to index](../README.md) · [Українська версія](Apfiltr_3.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `5AF8E57DEA97B7E081C741402566E9580410BE0445704D57CA71E58725870605` | `9681C0EC6A6AD03BBA26143C2F856F43B70FA2BD` | `995EBACAFBE57B22A5568F4B519803A4` |

## Metadata

- **Filename:** `Apfiltr_3.sys`
- **Size:** 605320 bytes
- **Architecture:** 0x8664
- **Company:** Alps Electric Co., Ltd.
- **Product:** Alps Touch Pad Driver
- **Description:** Alps Touch Pad Driver
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
