# `ntfs.sys`

[Назад до індексу](../README.uk.md) · [English version](ntfs.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `24B023140A6D162DB3FE0D701109FC0BE4FDD9EC65E1C40522934AE3CC0A28C6` | `7D51FCE87B96A2F32DCDCC64C3D23EB4754AB7CA` | `7BE24DA2E71B3BED7BBCE3C2AC7D5B6B` |

## Метадані

- **Ім'я файлу:** `ntfs.sys`
- **Розмір:** 3556856 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** NT File System Driver
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** —
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `page locking`, `physical memory mapping`, `process lookup`

**Imports:** `IoAllocateMdl`, `MmMapIoSpaceEx`, `MmProbeAndLockPages`, `PsLookupProcessByProcessId`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
