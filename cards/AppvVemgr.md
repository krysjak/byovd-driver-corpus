# `AppvVemgr.sys`

[Back to index](../README.md) · [Українська версія](AppvVemgr.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `C8BCD77030F948A6287ADDA728FCBA6B4297DEC9FE6A05CDECCEF624075C8AE1` | `A90FB6E87B9A7F2BD39FB6B267CFFF4A84259674` | `633A321028E777F0F5A9F055559F34EA` |

## Metadata

- **Filename:** `AppvVemgr.sys`
- **Size:** 218432 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** Microsoft Application Virtualization VE Manager Driver
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `process handle access`, `process termination`

**Imports:** `ZwOpenProcess`, `ZwTerminateProcess`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.
