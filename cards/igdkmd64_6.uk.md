# `igdkmd64_6.sys`

[Назад до індексу](../README.uk.md) · [English version](igdkmd64_6.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `EFC0A5E529F7B0E0587F0DB7DA2BED723229D42B1A0400381FCC66F82260E08B` | `805E54DBFAC4A41F663F84DEB53F792848DBE2BB` | `24BB7A4BC3B0A4C1F9ABD012ED51F9E2` |

## Метадані

- **Ім'я файлу:** `igdkmd64_6.sys`
- **Розмір:** 3797424 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel HD Graphics Drivers for Windows 8(R)
- **Опис:** Intel Graphics Kernel Mode Driver
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** — · **Немає перевірки probe:** —
- **У системах:** OEM package
- **Score:** 160

## Профіль можливостей

**Primitives:** `MDL allocation`, `contiguous physical allocation`, `driver loading`, `page locking`, `physical address resolution`, `physical memory mapping`, `process lookup`, `section mapping (kernel R/W surface)`

**Imports:** `IoAllocateMdl`, `MmAllocateContiguousMemory`, `MmGetPhysicalAddress`, `MmMapIoSpace`, `MmProbeAndLockPages`, `PsLookupProcessByProcessId`, `ZwLoadDriver`, `ZwMapViewOfSection`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
