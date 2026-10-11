# `mpsdrv.sys`

[Назад до індексу](../README.uk.md) · [English version](mpsdrv.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `D640F00F5E152782906D443981F7577DBAA1960058E27B7683BA029182F5A220` | `A3904FC35F0C5925DEB32A62D26EED1A649A23D5` | `B2A5127A97FF55134CADF6543F85836B` |

## Метадані

- **Ім'я файлу:** `mpsdrv.sys`
- **Розмір:** 114688 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Microsoft Protection Service Driver
- **Підпис:** unsigned
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `process handle access`

**Imports:** `ZwOpenProcess`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
