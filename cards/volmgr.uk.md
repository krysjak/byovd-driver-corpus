# `volmgr.sys`

[Назад до індексу](../README.uk.md) · [English version](volmgr.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `A546CBE5C7B0281545FD55672E75BDB4644313053FAED6021459BB62EF174D6D` | `7774A5ED0A1C9AA6FA975D8CDE45D561D929A0B3` | `0463124E8F5CBD9B30A57C2F98C853D2` |

## Метадані

- **Ім'я файлу:** `volmgr.sys` (Ідентичні копії: `volmgr_1.sys`)
- **Розмір:** 128488 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Volume Manager Driver
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`

**Imports:** `IoAllocateMdl`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
