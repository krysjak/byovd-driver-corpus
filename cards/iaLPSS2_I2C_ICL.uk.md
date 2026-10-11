# `iaLPSS2_I2C_ICL.sys`

[Назад до індексу](../README.uk.md) · [English version](iaLPSS2_I2C_ICL.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `ACC22D47A0BE443B5562DF6B510A3DEBF01D82CD3C3606A9E18CB7B44AD7A305` | `D17133ECAACF2296231FD0750C85DAA48FD48DFE` | `471CED25B1D6BA00E4B7B6627ABF80D1` |

## Метадані

- **Ім'я файлу:** `iaLPSS2_I2C_ICL.sys`
- **Розмір:** 200456 bytes
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
