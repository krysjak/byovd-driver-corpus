# `iaLPSS2_GPIO2_ICL.sys`

[Назад до індексу](../README.uk.md) · [English version](iaLPSS2_GPIO2_ICL.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `D981363E6B53D13960AB6C5587A2439A104864BA2B604D5EFDA049AB504CC782` | `0F4E9AD3B28DFF27D4A594F45DD1E807E50A33BB` | `A58D5A4BBFF60873E57E5D4AAB9EEB2B` |

## Метадані

- **Ім'я файлу:** `iaLPSS2_GPIO2_ICL.sys`
- **Розмір:** 132872 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel(R) Serial IO Driver
- **Опис:** Intel(R) Serial IO GPIO Driver v2
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
