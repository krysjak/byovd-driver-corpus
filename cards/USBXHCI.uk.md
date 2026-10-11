# `USBXHCI.SYS`

[Назад до індексу](../README.uk.md) · [English version](USBXHCI.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `AFF0F88D0B3908BFA349048F4E1586B1D06F5FB6237C050FFD3A3BF9898A4A48` | `B66CE5CD71F0AEA9B760E3E864F56B9FDEFB5C6A` | `ED69C801E98FC2E8F3671B362EBECC9D` |

## Метадані

- **Ім'я файлу:** `USBXHCI.SYS` (Ідентичні копії: `USBXHCI_1.SYS`)
- **Розмір:** 792032 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** USB XHCI Driver
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11 · **Задокументовано:** 2024-09-10
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** In the wild
- **Score:** 0 · **MITRE:** T1068

## Профіль можливостей

**Primitives:** `MDL allocation`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmMapIoSpaceEx`

## Задокументоване використання (LOLDrivers)

**Опис:** Sophos, from time to time, has observed a threat actor deploy variants of Poortry on different machines within a single estate during an attack. These variants contain the same payload, but signed with a different certificate than the driver first seen used during the attack.

```
sc.exe create driver_ef9d653a.sys binPath=C:\windows\temp\driver_ef9d653a.sys type=kernel && sc.exe start driver_ef9d653a.sys
```

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
