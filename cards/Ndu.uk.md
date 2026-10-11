# `Ndu.sys`

[Назад до індексу](../README.uk.md) · [English version](Ndu.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `4A0B302C40FCBBE143412F99D811BAF59241EAA27271DA43100581C11B1E4C7E` | `3168C7EFE2AF3E3F3876C88923EF8BD580C49F34` | `416D3389055D85231A4B8E18686362D5` |

## Метадані

- **Ім'я файлу:** `Ndu.sys`
- **Розмір:** 192512 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Windows Network Data Usage Monitoring Driver
- **Підпис:** unsigned
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `process lookup`

**Imports:** `PsLookupProcessByProcessId`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
