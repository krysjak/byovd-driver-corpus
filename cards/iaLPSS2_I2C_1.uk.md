# `iaLPSS2_I2C_1.sys`

[Назад до індексу](../README.uk.md) · [English version](iaLPSS2_I2C_1.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `513363DAB8EE96F78A7400E78A0199ACB4EB12580EEE655F60A9BCB93BD529CC` | `C92F31BD7C821D64AF5A9C1EDA998C16112A5C0E` | `35AA788A33F360F62799CB5FB313F50A` |

## Метадані

- **Ім'я файлу:** `iaLPSS2_I2C_1.sys`
- **Розмір:** 195680 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel(R) Serial IO Driver
- **Опис:** Intel(R) Serial IO I2C Driver v2
- **Підпис:** signed
- **Джерело:** `oem:hp`
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
