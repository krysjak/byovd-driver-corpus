# `intelppm.sys`

[Назад до індексу](../README.uk.md) · [English version](intelppm.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `2034912ED671999583B0394B12F3AA4301A428815DE12CDFA1D33926F83B112B` | `0625795F33D4175B433D3D828EF21E89C1597002` | `73D298526484CD550D2F1857D1B04F9A` |

## Метадані

- **Ім'я файлу:** `intelppm.sys` (Ідентичні копії: `intelppm_2.sys`)
- **Розмір:** 300512 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Processor Device Driver
- **Підпис:** signed
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
