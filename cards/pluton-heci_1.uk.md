# `pluton-heci_1.sys`

[Назад до індексу](../README.uk.md) · [English version](pluton-heci_1.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `688019578FB97E91321249CF55B6C848CC679C8C5B8B465F89F2D360BA3B115A` | `1039C75FCB1716FCC442F01368B6EBC71C1BD07C` | `A671486F71AC22D8C5B5256BDED157E3` |

## Метадані

- **Ім'я файлу:** `pluton-heci_1.sys` (Ідентичні копії: `pluton-heci_2.sys`)
- **Розмір:** 79256 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Pluton HECI Device Driver
- **Підпис:** signed
- **Джерело:** `local`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Live system
- **Score:** 90

## Профіль можливостей

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpace`, `MmMapIoSpaceEx`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
