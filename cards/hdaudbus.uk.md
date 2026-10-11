# `hdaudbus.sys`

[Назад до індексу](../README.uk.md) · [English version](hdaudbus.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `7B2C4E15010266558096F2B5AE57550601D6F70ACC054E8603E702D349DDEBB4` | `F49A5278C26227E7E3E4A1743462A40BE4545F5B` | `0AA5D597380B2585FDAC7E53C0660F30` |

## Метадані

- **Ім'я файлу:** `hdaudbus.sys` (Ідентичні копії: `hdaudbus_1.sys`)
- **Розмір:** 204800 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** High Definition Audio Bus Driver
- **Підпис:** unsigned
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `physical address resolution`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmMapIoSpaceEx`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
