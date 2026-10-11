# `VSTBS36.SYS`

[Назад до індексу](../README.uk.md) · [English version](VSTBS36.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `111E18952FB1F1B9D2059D8F6880FE1D5996C5D193EB8FBB2757826123739F2A` | `6957ABABBC4141A4EBD589B81AD400B996D22446` | `A42B22601CC2754428B5F82E040FD1C7` |

## Метадані

- **Ім'я файлу:** `VSTBS36.SYS`
- **Розмір:** 287744 bytes
- **Архітектура:** 0x8664
- **Компанія:** Conexant Systems, Inc.
- **Продукт:** SoftK56 Modem Driver
- **Опис:** HSF_HWB3 WDM driver
- **Підпис:** unsigned
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmMapIoSpace`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
