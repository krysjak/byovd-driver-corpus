# `rtots640x64.sys`

[Back to index](../README.md) · [Українська версія](rtots640x64.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `F62D9F3E8DA87C45605FE8B8D2F365BC005F4784B49DCF40C5E87E5593AEDB5B` | `5265CF4BE90F577755D293EE8356108D82F634A6` | `61DC9559AFD1E1C9195C7EC0D27A8259` |

## Metadata

- **Filename:** `rtots640x64.sys`
- **Size:** 1460736 bytes
- **Architecture:** 0x8664
- **Company:** Realtek                                        
- **Product:** Realtek 8125/8126/8136/8168/8169 PCI/PCIe Adapters                                        
- **Description:** Realtek 8125/8126/8136/8168/8169 NDIS 6.40 64-bit Driver                                        
- **Signature:** signed
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
