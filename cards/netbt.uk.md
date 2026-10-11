# `netbt.sys`

[Назад до індексу](../README.uk.md) · [English version](netbt.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `E612D892A2D5AF0C2D3721F34C30074F5BB8178F6A94D60243BE74260A9601F1` | `F041BF97046A138334DDB662BE99739669448585` | `F01D95DB170DE8DD24673D471237C960` |

## Метадані

- **Ім'я файлу:** `netbt.sys`
- **Розмір:** 360448 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** MBT Transport driver
- **Підпис:** unsigned
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `process address-space attach`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
