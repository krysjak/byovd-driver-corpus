# `rtcx21x64.sys`

[Back to index](../README.md) · [Українська версія](rtcx21x64.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `3C653B13438497D5ED8F1A0F7F24C14C0EC9FFC7E324135C29EB591BF1AAEA94` | `BD796381DED9399E565C6415EC75E50F07E3DEF0` | `F1FF821EC7AEEB7CD2FBCC58FE745E80` |

## Metadata

- **Filename:** `rtcx21x64.sys`
- **Size:** 539648 bytes
- **Architecture:** 0x8664
- **Company:** Realtek                                        
- **Product:** Realtek PCIe Adapter                                        
- **Description:** Realtek NetAdapter Driver                                        
- **Signature:** unsigned
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmMapIoSpaceEx`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.
