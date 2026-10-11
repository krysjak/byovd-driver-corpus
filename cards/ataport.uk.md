# `ataport.sys`

[Назад до індексу](../README.uk.md) · [English version](ataport.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `0DFC272C731BF3E86A68F89A75E7352CFDAD2A406756B806668711DDE6FEEC35` | `9F1295DA6A58497EAAFDE960BD279D0025AC5D9B` | `8774F26CEA89C4F3C328984897773FF2` |

## Метадані

- **Ім'я файлу:** `ataport.sys` (Ідентичні копії: `ataport_1.sys`)
- **Розмір:** 284128 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** ATAPI Driver Extension
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `page locking`, `physical address resolution`, `physical memory mapping`, `process address-space attach`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmGetPhysicalAddress`, `MmMapIoSpaceEx`, `MmProbeAndLockPages`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
