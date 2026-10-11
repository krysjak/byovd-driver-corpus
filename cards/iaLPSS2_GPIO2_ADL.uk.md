# `iaLPSS2_GPIO2_ADL.sys`

[Назад до індексу](../README.uk.md) · [English version](iaLPSS2_GPIO2_ADL.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `818D4E3228A9A52EE86FADE0EF07686FB625F5747F8A3DCBCA7A40AFF2C5C3E8` | `D27F254488A0387F6C41CA5EE8B431D00C2603AE` | `974D04F22B23B9BAEF565340697F8B55` |

## Метадані

- **Ім'я файлу:** `iaLPSS2_GPIO2_ADL.sys`
- **Розмір:** 150616 bytes
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
