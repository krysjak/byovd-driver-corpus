# `dxgmms2.sys`

[Назад до індексу](../README.uk.md) · [English version](dxgmms2.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `27898B834168483FC83E93294C4C6CDB4908E3056FC127F0876422F9F9FEAF41` | `8481B1404227D2FCF20834AF5004CFBE4F4AA4E5` | `3E16C3050CA6FAE7F93710FA61DB06AE` |

## Метадані

- **Ім'я файлу:** `dxgmms2.sys`
- **Розмір:** 1197528 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** DirectX Graphics MMS
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** —
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `page locking`, `physical address resolution`, `physical memory mapping`, `process address-space attach`, `process handle access`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmGetPhysicalAddress`, `MmMapIoSpaceEx`, `MmProbeAndLockPages`, `ZwOpenProcess`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
