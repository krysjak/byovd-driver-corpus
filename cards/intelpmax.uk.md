# `intelpmax.sys`

[Назад до індексу](../README.uk.md) · [English version](intelpmax.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `AF0C3C9AE1DB6F60C65C0A046F01C740BD47E10B73FBF0A3A05BB0AB8542362B` | `DF2BEE9186B29703290E05E22F06CC1DB931371C` | `76DC389A4F660AE3688B1683A566F162` |

## Метадані

- **Ім'я файлу:** `intelpmax.sys` (Ідентичні копії: `intelpmax_1.sys`)
- **Розмір:** 65536 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Intel Power Limit Driver
- **Підпис:** unsigned
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
