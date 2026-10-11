# `hdaudbus_2.sys`

[Назад до індексу](../README.uk.md) · [English version](hdaudbus_2.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `C0BC942BD672FF3F8C6EDD8AFB4AE140AF3EF411CE4C6033B4A8FC3A584E73E3` | `F869E48A7EC0B2EA5CA9D411BDF14100284366F0` | `916AA4C5B4C1AB61040AA0C0E11B83E2` |

## Метадані

- **Ім'я файлу:** `hdaudbus_2.sys`
- **Розмір:** 204800 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** High Definition Audio Bus Driver
- **Підпис:** unsigned
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `physical address resolution`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmMapIoSpaceEx`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
