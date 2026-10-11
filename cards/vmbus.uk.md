# `vmbus.sys`

[Назад до індексу](../README.uk.md) · [English version](vmbus.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `3CC7F47ADAAE3840FD4DA88185F3E10A9F783E04ED9ABC8104923D22FCF1F2BA` | `5E2DF3CAE9EF52EB354FC357303CB5D520F1F576` | `E82D06B490EAABE0E9ABC93A0C935841` |

## Метадані

- **Ім'я файлу:** `vmbus.sys` (Ідентичні копії: `vmbus_1.sys`)
- **Розмір:** 210424 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Microsoft Hyper-V Virtual Machine Bus Child Driver
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `page locking`, `physical address resolution`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmMapIoSpaceEx`, `MmProbeAndLockPages`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
