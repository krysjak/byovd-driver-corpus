# `Netwtw06.sys`

[Назад до індексу](../README.uk.md) · [English version](Netwtw06.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `1D8CE74ED07FA3AABFAAAEB449A8401F9BCAD6FE93D31FC4EB11835CD978785D` | `3018E69252982935E6D9F27817D1127AEA2717BF` | `E495B2F434628B91EFDD2BAF642CC9F9` |

## Метадані

- **Ім'я файлу:** `Netwtw06.sys`
- **Розмір:** 8803328 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel® Wireless WiFi Link Adapter
- **Опис:** Intel® Wireless WiFi Link Driver
- **Підпис:** unsigned
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpace`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
