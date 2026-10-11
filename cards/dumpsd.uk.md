# `dumpsd.sys`

[Назад до індексу](../README.uk.md) · [English version](dumpsd.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `923F7B0ADDAC1717C87E47CADE65938D42985A7B0EF799D0B3ABFA8A1F3941BA` | `93660116645B28867123720E2BCAF9906F123560` | `B5105BC2A71948859D4BEA420128B852` |

## Метадані

- **Ім'я файлу:** `dumpsd.sys` (Ідентичні копії: `dumpsd_1.sys`)
- **Розмір:** 234960 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** SD Crashdump Port Driver
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `physical address resolution`, `physical memory mapping`

**Imports:** `MmGetPhysicalAddress`, `MmMapIoSpaceEx`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
