# `spaceparser.sys`

[Назад до індексу](../README.uk.md) · [English version](spaceparser.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `C293F6A1D770CB3A564546D1D7989EED25A8BAA7B6F53CD5720CEA3562EED275` | `11331BB77FC1F8A9A702DF8452A2A138BFD79ADF` | `B0448349AAD36CAF0C6E598672B7D7E0` |

## Метадані

- **Ім'я файлу:** `spaceparser.sys`
- **Розмір:** 86016 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Storage Spaces Parser driver
- **Підпис:** unsigned
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`

**Imports:** `IoAllocateMdl`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
