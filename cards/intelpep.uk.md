# `intelpep.sys`

[Назад до індексу](../README.uk.md) · [English version](intelpep.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `9C1E78F3AD76ADF256994D044C3F89FA960102612D1F045A6937011930FF4925` | `7F4B9B22D1B25C04B2A6B275A626D8D3F568C42A` | `C26D8ACCB6BA137B3ACCDCF58C564793` |

## Метадані

- **Ім'я файлу:** `intelpep.sys` (Ідентичні копії: `intelpep_1.sys`)
- **Розмір:** 657888 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Intel Power Engine Plugin
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
