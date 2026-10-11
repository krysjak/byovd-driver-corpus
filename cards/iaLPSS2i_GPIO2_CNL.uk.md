# `iaLPSS2i_GPIO2_CNL.sys`

[Назад до індексу](../README.uk.md) · [English version](iaLPSS2i_GPIO2_CNL.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `E353D90D0B79A70F976FD5EA1CB7E25A97835E25116962EA035424715B2F43FE` | `B069D53CE6CE3A5EF35F985285D2BF7F6114C8CA` | `87DDDAE1693484BD0A210C877BDA00C2` |

## Метадані

- **Ім'я файлу:** `iaLPSS2i_GPIO2_CNL.sys` (Ідентичні копії: `iaLPSS2i_GPIO2_CNL_1.sys`)
- **Розмір:** 112128 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel(R) Serial IO Driver
- **Опис:** Intel(R) Serial IO GPIO Driver v2
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
