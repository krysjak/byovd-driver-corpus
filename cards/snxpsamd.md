# `snxpsamd.sys`

[Back to index](../README.md) · [Українська версія](snxpsamd.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `22BD1A35A70DC998ACF94ECD076151168A117A8C883D90EF9EB0E5FEDC9399EF` | `08715462C549E84713B6C1CF1106091DDAA63187` | `EFEE04C916F0348B38FAE3C20CEC38D3` |

## Metadata

- **Filename:** `snxpsamd.sys`
- **Size:** 111520 bytes
- **Architecture:** 0x8664
- **Company:** SUNIX Co., Ltd.
- **Product:** SUNIX Multi I/O Card
- **Description:** SUNIX Serial Driver (x64)
- **Signature:** signed
- **Source:** `oem:hp`
- **Added to repo:** 2026-10-11 · **Documented:** 2026-08-31
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** yes
- **On systems:** In the wild
- **Score:** 105 · **MITRE:** T1068

## Capability profile

**Primitives:** `physical address resolution`, `physical memory mapping`

**Imports:** `MmGetPhysicalAddress`, `MmMapIoSpace`

## Documented usage (LOLDrivers)

**Description:** SUNIX Serial Driver x64 version 10.1.0.0 is affected by CVE-2024-55412. This exact signed build exposes raw I/O-port operations to low-privilege callers through IOCTLs including 0x9C403C04 and 0x9C403C08. An attacker can use the unrestricted port read/write primitives to disclose information, tamper with privileged hardware state, and elevate privileges.

```
sc.exe create snxpsamd type= kernel binPath= C:\\windows\\temp\\snxpsamd.sys && sc.exe start snxpsamd
```

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.
