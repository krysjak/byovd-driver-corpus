# `Netwbw02.sys`

[Назад до індексу](../README.uk.md) · [English version](Netwbw02.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `B8CB13863C1F0C589C008E191A393DF241F3067DD7CADE02B3B7D36B28BBA2ED` | `C0541D17C4B0293FC97F20F46E53CEF6D606B9FC` | `1F91B1E5FD41BDC3DF8AFFB81C8AA277` |

## Метадані

- **Ім'я файлу:** `Netwbw02.sys`
- **Розмір:** 3485696 bytes
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
