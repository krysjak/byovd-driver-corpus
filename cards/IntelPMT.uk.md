# `IntelPMT.sys`

[Назад до індексу](../README.uk.md) · [English version](IntelPMT.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `A05600E18B156ADC34AA848FF7769C8FD90BBEF6A6F4C4DCFE5BA38D531AB584` | `C1E85BAF8E6B7FC5D1894353D971E0F6AB62B17D` | `541D08852BFE62DEE0A2BB3A94F7E83F` |

## Метадані

- **Ім'я файлу:** `IntelPMT.sys` (Ідентичні копії: `IntelPMT_1.sys`)
- **Розмір:** 88520 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Intel Platform Monitoring Driver
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
