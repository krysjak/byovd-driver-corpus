# `igdkmd64_11.sys`

[Назад до індексу](../README.uk.md) · [English version](igdkmd64_11.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `594D4FBF6FD2916F61F834DC862DB48CF0C3A1A3A717F3A60831556238FA9C40` | `68046B4B55BB0A78A8CA45F3D7551017076F05B3` | `608383295B37DB4AD1E02A8058108379` |

## Метадані

- **Ім'я файлу:** `igdkmd64_11.sys`
- **Розмір:** 15499816 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel HD Graphics Drivers for Windows(R)
- **Опис:** Intel Graphics Kernel Mode Driver
- **Підпис:** signed
- **Джерело:** `oem:hp`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** —
- **У системах:** OEM package
- **Score:** 140

## Профіль можливостей

**Primitives:** `MDL allocation`, `contiguous physical allocation`, `driver loading`, `page locking`, `physical address resolution`, `physical memory mapping`, `process lookup`, `section mapping (kernel R/W surface)`

**Imports:** `IoAllocateMdl`, `MmAllocateContiguousMemory`, `MmGetPhysicalAddress`, `MmMapIoSpace`, `MmProbeAndLockPages`, `PsLookupProcessByProcessId`, `ZwLoadDriver`, `ZwMapViewOfSection`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
