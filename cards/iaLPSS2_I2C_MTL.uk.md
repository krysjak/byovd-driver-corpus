# `iaLPSS2_I2C_MTL.sys`

[Назад до індексу](../README.uk.md) · [English version](iaLPSS2_I2C_MTL.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `5523A8FDE7F2FD820976D9075C76B28FB6354BD127FF86C47D72068B49A186C7` | `396F84F76A77FD0FF125F4078D90E6240F444897` | `3B95F016A91F6E796754A301B7851642` |

## Метадані

- **Ім'я файлу:** `iaLPSS2_I2C_MTL.sys`
- **Розмір:** 212480 bytes
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
