# `Dumpstorport.sys`

[Назад до індексу](../README.uk.md) · [English version](Dumpstorport.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `64C11EB22AD2F95060A7918CFEF9D512C7E4143EFA16260BC978C7A3EE1A7B0C` | `B76B1B5C6991A0BAB5D12630778BB623AAA2F40A` | `1032E83839E2DDE72D5B30CD64AF7D4C` |

## Метадані

- **Ім'я файлу:** `Dumpstorport.sys`
- **Розмір:** 108008 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Storport Dump Driver
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
