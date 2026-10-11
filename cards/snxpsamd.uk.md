# `snxpsamd.sys`

[Назад до індексу](../README.uk.md) · [English version](snxpsamd.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `22BD1A35A70DC998ACF94ECD076151168A117A8C883D90EF9EB0E5FEDC9399EF` | `08715462C549E84713B6C1CF1106091DDAA63187` | `EFEE04C916F0348B38FAE3C20CEC38D3` |

## Метадані

- **Ім'я файлу:** `snxpsamd.sys`
- **Розмір:** 111520 bytes
- **Архітектура:** 0x8664
- **Компанія:** SUNIX Co., Ltd.
- **Продукт:** SUNIX Multi I/O Card
- **Опис:** SUNIX Serial Driver (x64)
- **Підпис:** signed
- **Джерело:** `oem:hp`
- **Додано до репо:** 2026-10-11 · **Задокументовано:** 2026-08-31
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** так
- **У системах:** In the wild
- **Score:** 105 · **MITRE:** T1068

## Профіль можливостей

**Primitives:** `physical address resolution`, `physical memory mapping`

**Imports:** `MmGetPhysicalAddress`, `MmMapIoSpace`

## Задокументоване використання (LOLDrivers)

**Опис:** SUNIX Serial Driver x64 version 10.1.0.0 is affected by CVE-2024-55412. This exact signed build exposes raw I/O-port operations to low-privilege callers through IOCTLs including 0x9C403C04 and 0x9C403C08. An attacker can use the unrestricted port read/write primitives to disclose information, tamper with privileged hardware state, and elevate privileges.

```
sc.exe create snxpsamd type= kernel binPath= C:\\windows\\temp\\snxpsamd.sys && sc.exe start snxpsamd
```

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
