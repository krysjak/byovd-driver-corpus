# `usbport_2.sys`

[Назад до індексу](../README.uk.md) · [English version](usbport_2.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `5E94DFCE103E5B57A6184CA0C47848DA2EEACC7C87E15BD739D081A3A2AA7C19` | `87898F93B610A665F1F9F2DD03EC76774032B109` | `819477B95D1951FE6F4B1854CDE38813` |

## Метадані

- **Ім'я файлу:** `usbport_2.sys` (Ідентичні копії: `usbport_3.sys`)
- **Розмір:** 509328 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** USB 1.1 & 2.0 Port Driver
- **Підпис:** signed
- **Джерело:** `local`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** так
- **У системах:** Live system
- **Score:** 125

## Профіль можливостей

**Primitives:** `MDL allocation`, `page locking`, `physical address resolution`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmMapIoSpaceEx`, `MmProbeAndLockPages`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
