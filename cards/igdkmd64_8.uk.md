# `igdkmd64_8.sys`

[Назад до індексу](../README.uk.md) · [English version](igdkmd64_8.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `A751622F141CE464DD8A97B69DFDBD9E29B3518ACA40B33007FD15A474AB2002` | `D02399D206E34F7ADBCA83F6B8E83CFC3EB50834` | `2440CE15EDFBDA2CBEB63ADB9C1988E4` |

## Метадані

- **Ім'я файлу:** `igdkmd64_8.sys`
- **Розмір:** 26113296 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel HD Graphics Drivers for Windows(R)
- **Опис:** Intel Graphics Kernel Mode Driver
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** —
- **У системах:** OEM package
- **Score:** 140

## Профіль можливостей

**Primitives:** `MDL allocation`, `contiguous physical allocation`, `driver loading`, `page locking`, `physical address resolution`, `physical memory mapping`, `process address-space attach`, `process handle access`, `process lookup`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmAllocateContiguousMemory`, `MmGetPhysicalAddress`, `MmMapIoSpace`, `MmProbeAndLockPages`, `PsLookupProcessByProcessId`, `ZwLoadDriver`, `ZwOpenProcess`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
