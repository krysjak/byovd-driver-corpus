# `spaceport_1.sys`

[Назад до індексу](../README.uk.md) · [English version](spaceport_1.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `E26F516FA887E17143A7D53A047B2BF180DE704EFD63A45A41A409BA816D8ED7` | `64C76D8F29E75ED4E5FCC047687EF592A10C13EA` | `0835509BD13E767E9D645C4F9CBEF179` |

## Метадані

- **Ім'я файлу:** `spaceport_1.sys` (Ідентичні копії: `spaceport_3.sys`)
- **Розмір:** 1021344 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Storage Spaces Driver
- **Підпис:** signed
- **Джерело:** `local`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** так
- **У системах:** Live system
- **Score:** 85

## Профіль можливостей

**Primitives:** `MDL allocation`, `page locking`, `process address-space attach`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmProbeAndLockPages`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
