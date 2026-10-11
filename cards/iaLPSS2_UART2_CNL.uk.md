# `iaLPSS2_UART2_CNL.sys`

[Назад до індексу](../README.uk.md) · [English version](iaLPSS2_UART2_CNL.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `DC8D280A746872D0C7F23A53199F48DA5B8CC48BE048F8608ED3B5AF5EFC22AE` | `4AF625AA065F5C09EF8B3D94E616CC1C5C259769` | `7C9DAA00F31AE0E09292AF0704038705` |

## Метадані

- **Ім'я файлу:** `iaLPSS2_UART2_CNL.sys`
- **Розмір:** 305928 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel(R) Serial IO Driver
- **Опис:** Intel(R) Serial IO UART Driver
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
