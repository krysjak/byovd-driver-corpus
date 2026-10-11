# `ufxsynopsys.sys`

[Назад до індексу](../README.uk.md) · [English version](ufxsynopsys.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `4B8938777B92F4F1B3199DEF96F03E710CC22D8A2720297F3F1B53A696D3347F` | `71DB31410B116C6AFD749D3AA4AE6A3277DA8946` | `186850C50025B806B391D69E916EE770` |

## Метадані

- **Ім'я файлу:** `ufxsynopsys.sys` (Ідентичні копії: `ufxsynopsys_1.sys`)
- **Розмір:** 198064 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** UFX Synopsys Client Driver
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
