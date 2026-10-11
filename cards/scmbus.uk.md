# `scmbus.sys`

[Назад до індексу](../README.uk.md) · [English version](scmbus.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `167D74D8F1A0815409A6A315FA55BB416FE8584280A89393A98ACA1A6A245327` | `792C707AC99F780B7B72F2840B164A317A4C83FA` | `036139D75294C8DA95D212CB5E543132` |

## Метадані

- **Ім'я файлу:** `scmbus.sys` (Ідентичні копії: `scmbus_2.sys`)
- **Розмір:** 259576 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Storage Class Memory Bus Driver
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpaceEx`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
