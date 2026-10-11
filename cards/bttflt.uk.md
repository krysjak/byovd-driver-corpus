# `bttflt.sys`

[Назад до індексу](../README.uk.md) · [English version](bttflt.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `0F65089C4A1B84B51D46CB758FE06AD3651EEECC72ED4A82DAD15BC419F60AD5` | `C94903347F972FC60AB2A92D6D05319BD14B9BBF` | `EBB4AC45D7A7040352CD206D0201B31C` |

## Метадані

- **Ім'я файлу:** `bttflt.sys` (Ідентичні копії: `bttflt_1.sys`)
- **Розмір:** 79176 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** VHD BTT Filter Driver
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `physical address resolution`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmMapIoSpaceEx`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
