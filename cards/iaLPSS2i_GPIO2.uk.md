# `iaLPSS2i_GPIO2.sys`

[Назад до індексу](../README.uk.md) · [English version](iaLPSS2i_GPIO2.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `6FF5D13EF69E8FBCB4772C7B5C4D5770C78E0B29F9164FA1611EFDE91CE876BE` | `BFB14D74BF8088F99E96C6BBD036C320F913E7F7` | `6C3EDE394C71D5A67A504F55E35B6F47` |

## Метадані

- **Ім'я файлу:** `iaLPSS2i_GPIO2.sys` (Ідентичні копії: `iaLPSS2i_GPIO2_1.sys`)
- **Розмір:** 79360 bytes
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
