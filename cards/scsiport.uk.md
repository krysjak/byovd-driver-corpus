# `scsiport.sys`

[Назад до індексу](../README.uk.md) · [English version](scsiport.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `0644B97F847EF3F1C9CB053D50BE73F043E59278D3748B84130E459C1B39A83A` | `29BC689219960B096E290B4B13CA6CFD6F831329` | `8F3D558B51BF137B516FCC8134AC2964` |

## Метадані

- **Ім'я файлу:** `scsiport.sys`
- **Розмір:** 226736 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** SCSI Port Driver
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `page locking`, `physical address resolution`, `physical memory mapping`, `process address-space attach`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmGetPhysicalAddress`, `MmMapIoSpace`, `MmProbeAndLockPages`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
