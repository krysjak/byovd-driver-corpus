# `iaLPSS2i_I2C_CNL.sys`

[Назад до індексу](../README.uk.md) · [English version](iaLPSS2i_I2C_CNL.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `F105EDD16E38F5C0044CC7139E4084A04B0AE3212171A1C7F6FE759F3F5F77FC` | `2D48737FB6DC8ED9B6D50FB06867E91C72DC50F9` | `897478D8FACEAE8681F6F3502201EC68` |

## Метадані

- **Ім'я файлу:** `iaLPSS2i_I2C_CNL.sys` (Ідентичні копії: `iaLPSS2i_I2C_CNL_1.sys`)
- **Розмір:** 177152 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel(R) Serial IO Driver
- **Опис:** Intel(R) Serial IO I2C Driver v2
- **Підпис:** unsigned
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpaceEx`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
