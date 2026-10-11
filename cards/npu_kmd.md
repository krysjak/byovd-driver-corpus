# `npu_kmd.sys`

[Back to index](../README.md) · [Українська версія](npu_kmd.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `A06669F848BDF897B6042D1C2082AB71123F0CB362A4CE2641A5C6F70B242018` | `57B6C619ED61E90152492D1B8BFF04F29A661020` | `0A3189640984010926FBD6BCA30C0369` |

## Metadata

- **Filename:** `npu_kmd.sys`
- **Size:** 3871712 bytes
- **Architecture:** 0x8664
- **Company:** Intel(R) Corporation
- **Product:** Intel(R) NPU Driver
- **Description:** Kernel Mode Driver
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** —
- **On systems:** OEM package
- **Score:** 65

## Capability profile

**Primitives:** `MDL allocation`, `contiguous physical allocation`, `driver loading`, `page locking`, `physical address resolution`

**Imports:** `IoAllocateMdl`, `MmAllocateContiguousMemory`, `MmGetPhysicalAddress`, `MmProbeAndLockPages`, `ZwLoadDriver`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.
