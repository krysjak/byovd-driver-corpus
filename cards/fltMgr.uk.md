# `fltMgr.sys`

[Назад до індексу](../README.uk.md) · [English version](fltMgr.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `76B7AB968A533637E4F1D8BE1CA66B0231CE1C3048C3127549CAEE15A79D5AC6` | `1472BB0F8EFD0391F93EF9EE3485DCEEACD64615` | `EA06C19624940A7FEAB6A9B35CCBCD86` |

## Метадані

- **Ім'я файлу:** `fltMgr.sys`
- **Розмір:** 611792 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Microsoft Filesystem Filter Manager
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** —
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `driver loading`, `page locking`, `process lookup`

**Imports:** `IoAllocateMdl`, `MmProbeAndLockPages`, `PsLookupProcessByProcessId`, `ZwLoadDriver`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
