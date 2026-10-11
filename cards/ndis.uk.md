# `ndis.sys`

[Назад до індексу](../README.uk.md) · [English version](ndis.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `221AE7328A432E9DA76A80C029596B1BEE0A06723A675E8DDB286B23CEDD685A` | `CD4471E4745D073A59BA3D93809096DFE13E82DF` | `12497FE12A8C5BB376E1EBB2DB4C31CC` |

## Метадані

- **Ім'я файлу:** `ndis.sys`
- **Розмір:** 1828352 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Network Driver Interface Specification (NDIS)
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `driver loading`, `physical address resolution`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmMapIoSpaceEx`, `ZwLoadDriver`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
