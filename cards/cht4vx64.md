# `cht4vx64.sys`

[Back to index](../README.md) · [Українська версія](cht4vx64.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `9EC811C11EBF399A5C4FDDD07A9E63975F2145151306C8599F64DC35A0966EB0` | `39DD15E5B799B7EABA26D67AC38B583DB9CAF500` | `A31DAAEF9BA7D22DBFB68B7E9B17CD40` |

## Metadata

- **Filename:** `cht4vx64.sys` (Identical copies: `cht4vx64_1.sys`)
- **Size:** 1854880 bytes
- **Architecture:** 0x8664
- **Company:** Chelsio Communications
- **Product:** Chelsio Communications Unified Network I/O Controller
- **Description:** Virtual Bus Driver for Chelsio ® T5/T6 Chipset
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpaceEx`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.
