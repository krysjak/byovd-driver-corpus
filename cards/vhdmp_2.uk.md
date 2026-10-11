# `vhdmp_2.sys`

[Назад до індексу](../README.uk.md) · [English version](vhdmp_2.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `1046DB0C243ED7011ED907F9914C7F34574431F3BFAA0E9DE5CBCDD57AB9BA09` | `62DBBBCFA9D06CB16A8A6432AF983C2A92FBEEF7` | `B847F52622379A997CC6DBB280CA43BB` |

## Метадані

- **Ім'я файлу:** `vhdmp_2.sys` (Ідентичні копії: `vhdmp_3.sys`)
- **Розмір:** 1058200 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** VHD Miniport Driver
- **Підпис:** signed
- **Джерело:** `local`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** так
- **У системах:** Live system
- **Score:** 110

## Профіль можливостей

**Primitives:** `MDL allocation`, `page locking`, `physical address resolution`, `section mapping (kernel R/W surface)`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmProbeAndLockPages`, `ZwMapViewOfSection`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
