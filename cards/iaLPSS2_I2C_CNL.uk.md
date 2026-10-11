# `iaLPSS2_I2C_CNL.sys`

[Назад до індексу](../README.uk.md) · [English version](iaLPSS2_I2C_CNL.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `2A6866C3FEAD33BC5C850CFBE8DA064AF3F9D759FCD84308A25BE12B85019D25` | `63C233A4E3491164066F66766A49A0072DC7719C` | `5F5457824ABCBD53898945983330F515` |

## Метадані

- **Ім'я файлу:** `iaLPSS2_I2C_CNL.sys`
- **Розмір:** 196360 bytes
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
