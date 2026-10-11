# `iaLPSS2i_I2C.sys`

[Назад до індексу](../README.uk.md) · [English version](iaLPSS2i_I2C.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `3F1F9EC7571D0F82D3F5BBA298965491260708F05EBAAA2CC23483521A5FF079` | `7C971D0A702EA48481C9FCA3AE127528DBEDAE20` | `149F1260537C4F68C3F67C363B62F3C5` |

## Метадані

- **Ім'я файлу:** `iaLPSS2i_I2C.sys` (Ідентичні копії: `iaLPSS2i_I2C_1.sys`)
- **Розмір:** 171520 bytes
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
