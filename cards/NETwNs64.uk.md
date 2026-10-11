# `NETwNs64.sys`

[Назад до індексу](../README.uk.md) · [English version](NETwNs64.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `898DCBBBF94875059CD328B0FC75BE36A4E3DD471C6E28BFAE064BCF84349518` | `DEA0FEECC37BDBA5FD2845B3A0CB5C6FEFF1F5E3` | `57B9C04D673F236D41FAB03842C8640B` |

## Метадані

- **Ім'я файлу:** `NETwNs64.sys`
- **Розмір:** 8604672 bytes
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
