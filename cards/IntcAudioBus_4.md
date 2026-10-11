# `IntcAudioBus_4.sys`

[Back to index](../README.md) · [Українська версія](IntcAudioBus_4.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `1421A779553E0FE99C62997EE3E3E47104C93190DF7DA42C389918D10768F570` | `F035478B6832F10500A3144BAAE56593FEFFE87C` | `B5E0BDDBAD508FDA5AA09A0076160F8A` |

## Metadata

- **Filename:** `IntcAudioBus_4.sys`
- **Size:** 320952 bytes
- **Architecture:** 0x8664
- **Company:** Intel(R) Corporation
- **Product:** Intel(R) Smart Sound Technology BUS
- **Description:** Intel(R) Smart Sound Technology BUS
- **Signature:** signed
- **Source:** `oem:dell`
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
