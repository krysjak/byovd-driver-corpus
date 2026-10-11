# `usbport.sys`

[Назад до індексу](../README.uk.md) · [English version](usbport.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `D18A63273C3DC26D1EA4550CC63DC59F44FD523C7CF6190FE151BE0D95D3989A` | `AAA88F3E9A94BC4E3A410352562C9416B2B93553` | `351520B1C913628D7B2297A243F00FE8` |

## Метадані

- **Ім'я файлу:** `usbport.sys` (Ідентичні копії: `usbport_1.sys`)
- **Розмір:** 509400 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** USB 1.1 & 2.0 Port Driver
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `page locking`, `physical address resolution`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmMapIoSpaceEx`, `MmProbeAndLockPages`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
