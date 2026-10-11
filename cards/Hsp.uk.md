# `Hsp.sys`

[Назад до індексу](../README.uk.md) · [English version](Hsp.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `54A4374AE70C31479C3BFC6FA22B9051880953E81AE93E2F560CFF170400BF89` | `8113DF48ED763C6DB0AFF9725E2590D2929F8182` | `E8B278887952F3421E2507171D603D9C` |

## Метадані

- **Ім'я файлу:** `Hsp.sys` (Ідентичні копії: `Hsp_1.sys`)
- **Розмір:** 124400 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** HSP Device Driver
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpaceEx`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
