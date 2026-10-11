# `pciidex_2.sys`

[Назад до індексу](../README.uk.md) · [English version](pciidex_2.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `712060C8D74BB89FA3F42E3C393897542FCBA22BDEB27466F1527D9E50905E1E` | `05E8E14ED1664DC766698604C28D8612C4DF4C39` | `2757525F9C17E13317BB4D5B2129BC0C` |

## Метадані

- **Ім'я файлу:** `pciidex_2.sys` (Ідентичні копії: `pciidex_3.sys`)
- **Розмір:** 91560 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** PCI IDE Bus Driver Extension
- **Підпис:** signed
- **Джерело:** `local`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Live system
- **Score:** 95

## Профіль можливостей

**Primitives:** `physical address resolution`, `physical memory mapping`

**Imports:** `MmGetPhysicalAddress`, `MmMapIoSpaceEx`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
