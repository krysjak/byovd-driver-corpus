# `errdev.sys`

[Назад до індексу](../README.uk.md) · [English version](errdev.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `42E3FA480F869C3E1D6BF2E78CB7665F19D5F399A8D359FFFA4B71805DAFEB9A` | `F224C163892665E4D85E009047C4761E175692B4` | `A96F659CB5EE6D897E16825BD255413F` |

## Метадані

- **Ім'я файлу:** `errdev.sys` (Ідентичні копії: `errdev_1.sys`)
- **Розмір:** 53248 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Error Device Driver
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
