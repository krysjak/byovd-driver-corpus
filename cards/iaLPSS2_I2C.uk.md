# `iaLPSS2_I2C.sys`

[Назад до індексу](../README.uk.md) · [English version](iaLPSS2_I2C.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `BE868253ECEEABB5FA6F75951277014D5CD229795FA102E7BD193D2C6A853FC0` | `8C06BC3649922538CD6F7786C0FF99B7CF6661F0` | `40046515B92BCFDBC928109C7D951F3A` |

## Метадані

- **Ім'я файлу:** `iaLPSS2_I2C.sys`
- **Розмір:** 195192 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel(R) Serial IO Driver
- **Опис:** Intel(R) Serial IO I2C Driver v2
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 60

## Профіль можливостей

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpaceEx`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
