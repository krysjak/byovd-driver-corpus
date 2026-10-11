# `storport.sys`

[Назад до індексу](../README.uk.md) · [English version](storport.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `6833A7666C673E0A80AFAD0D3889C5DB86226F51B65C1E97F57E19393A42B949` | `498380C05A4A1D4E09C5833B2946B3C9F4E96BEC` | `FD5D2482CC212AE920536B30AB23EAD7` |

## Метадані

- **Ім'я файлу:** `storport.sys`
- **Розмір:** 2602496 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Microsoft Storage Port Driver
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `driver loading`, `page locking`, `physical address resolution`, `physical memory mapping`, `process address-space attach`, `process handle access`, `section mapping (kernel R/W surface)`, `section object access`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmGetPhysicalAddress`, `MmMapIoSpace`, `MmMapIoSpaceEx`, `MmProbeAndLockPages`, `ZwLoadDriver`, `ZwMapViewOfSection`, `ZwOpenProcess`, `ZwOpenSection`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
