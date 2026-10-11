# `UcmUcsiAcpiClient.sys`

[Назад до індексу](../README.uk.md) · [English version](UcmUcsiAcpiClient.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `3931AC4925B70D4D84B36610C522DFBA373E98416FFA65CD6B468782AEB76B50` | `D8B5CED2715C8A69BC46CCE047106815505E37C8` | `349122C1D5464C4D2123DA5312C19760` |

## Метадані

- **Ім'я файлу:** `UcmUcsiAcpiClient.sys` (Ідентичні копії: `UcmUcsiAcpiClient_1.sys`)
- **Розмір:** 77824 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** UCM-UCSI ACPI Client Driver
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
