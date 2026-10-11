# `Netwsw00.sys`

[Назад до індексу](../README.uk.md) · [English version](Netwsw00.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `3D65A772C15440DF5895843185241D890CCDECA0E02DD6CF32CCB9B5849E31A4` | `90ECD5A5E941D8AAEDE618B6C472198699D509FD` | `272BB8C52BE106B5CC69171AF1D281D4` |

## Метадані

- **Ім'я файлу:** `Netwsw00.sys`
- **Розмір:** 11518976 bytes
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
