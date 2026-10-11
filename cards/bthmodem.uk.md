# `bthmodem.sys`

[Назад до індексу](../README.uk.md) · [English version](bthmodem.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `B4DD5BDF4119C92AC27F40F40FDA788D7C722814F03573598166A2EC909DE4A4` | `DBCD814A514F2D4A45F68E6C193E20D3919A1B84` | `5FC653281F80ECEF7C92F6D641C14277` |

## Метадані

- **Ім'я файлу:** `bthmodem.sys` (Ідентичні копії: `bthmodem_1.sys`)
- **Розмір:** 114688 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Bluetooth Communications Driver
- **Підпис:** unsigned
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `page locking`

**Imports:** `IoAllocateMdl`, `MmProbeAndLockPages`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
