# `UfxChipidea.sys`

[Назад до індексу](../README.uk.md) · [English version](UfxChipidea.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `C4E58AE7833097F4AB1264A9888F3790D819BC5F29A2BAD268F8DEC8730BF070` | `139084DFA88F2CC488F3D3A392C5A53E370D7B36` | `93064B010CDBEE52A44F6D55514B65F9` |

## Метадані

- **Ім'я файлу:** `UfxChipidea.sys`
- **Розмір:** 140592 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** UFX Chipidea Client Driver
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
