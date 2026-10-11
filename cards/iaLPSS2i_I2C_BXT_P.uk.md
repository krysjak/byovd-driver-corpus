# `iaLPSS2i_I2C_BXT_P.sys`

[Назад до індексу](../README.uk.md) · [English version](iaLPSS2i_I2C_BXT_P.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `BF354297A55713D9E2DD4044D42810C007733EE54D5A80D58B96DD279D92C716` | `58AF5951DFE87FA74D04EB6C171976089BA15BB8` | `3E641E905A6DBF29CBA1E72BBE349808` |

## Метадані

- **Ім'я файлу:** `iaLPSS2i_I2C_BXT_P.sys` (Ідентичні копії: `iaLPSS2i_I2C_BXT_P_1.sys`)
- **Розмір:** 175104 bytes
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
