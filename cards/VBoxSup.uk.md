# `VBoxSup.sys`

[Назад до індексу](../README.uk.md) · [English version](VBoxSup.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `55785D57968FD427D7332765D1D811832E8A43DF12668BE4C86F2B7BD18EFD55` | `EA20C5FB099CD005F4F19440B09C738912DE62C2` | `79BE1DEF92DC68B4178999C0CB01D958` |

## Метадані

- **Ім'я файлу:** `VBoxSup.sys` (Ідентичні копії: `VBoxSup_1.sys`)
- **Розмір:** 1057120 bytes
- **Архітектура:** 0x8664
- **Компанія:** Oracle and/or its affiliates
- **Продукт:** Oracle VirtualBox
- **Опис:** VirtualBox Support Driver
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** — · **Немає перевірки probe:** —
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `contiguous physical allocation`, `page locking`, `physical address resolution`, `physical memory mapping`, `process lookup`, `system information set`

**Imports:** `IoAllocateMdl`, `MmAllocateContiguousMemory`, `MmGetPhysicalAddress`, `MmMapIoSpace`, `MmProbeAndLockPages`, `PsLookupProcessByProcessId`, `ZwSetSystemInformation`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
