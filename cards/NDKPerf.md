# `NDKPerf.sys`

[Back to index](../README.md) · [Українська версія](NDKPerf.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `14C80E43627C3145FBA83528016B0FCE14A726C8130EAC03EF1C2AC83FB485BB` | `A6E12225CCE84D170C124FB85062D4C6E5A4000A` | `CE091328500FAAAD6953043BE257CB89` |

## Metadata

- **Filename:** `NDKPerf.sys`
- **Size:** 83448 bytes
- **Architecture:** 0x8664
- **Company:** —
- **Product:** —
- **Description:** —
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`

**Imports:** `IoAllocateMdl`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.
