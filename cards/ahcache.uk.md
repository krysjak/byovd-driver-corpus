# `ahcache.sys`

[Назад до індексу](../README.uk.md) · [English version](ahcache.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `8C57B690C2F0E3F1083A63B990460EE6E457F54C57C927BA7F8E09033CAD704A` | `859941DE94B034BBA550EC11D60E61AA8B35C18C` | `BEB45BB7476FA2064470146955C12862` |

## Метадані

- **Ім'я файлу:** `ahcache.sys`
- **Розмір:** 372736 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Application Compatibility Cache
- **Підпис:** unsigned
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** —
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `cross-process memory copy`, `process address-space attach`, `process lookup`, `section mapping (kernel R/W surface)`

**Imports:** `KeStackAttachProcess`, `MmCopyVirtualMemory`, `PsLookupProcessByProcessId`, `ZwMapViewOfSection`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
