# `iaLPSS2i_I2C_GLK.sys`

[Назад до індексу](../README.uk.md) · [English version](iaLPSS2i_I2C_GLK.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `A92487129B81376471C842B9932FF3A7B3ABBBB89797978E3FDEAF71A6FD5E3F` | `7DAF5030A0444B5DD6101875CDCAAEB90509C3CB` | `2ED3B41C7CB4101ACB15D84D8AB5AA9D` |

## Метадані

- **Ім'я файлу:** `iaLPSS2i_I2C_GLK.sys` (Ідентичні копії: `iaLPSS2i_I2C_GLK_1.sys`)
- **Розмір:** 177664 bytes
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
