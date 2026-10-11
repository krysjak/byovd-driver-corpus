# `fvevol.sys`

[Назад до індексу](../README.uk.md) · [English version](fvevol.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `AE24B5C515A06DB5655E6C1DAE4D172AD67CBA9400B10B7CCB52665871B1769B` | `8F251C34877627B4CC8C8DD9158A9B11C8E3437D` | `D1A5CB24F8DAE746AB68E1403A035719` |

## Метадані

- **Ім'я файлу:** `fvevol.sys`
- **Розмір:** 980448 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** BitLocker Drive Encryption Driver
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** —
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `page locking`, `physical address resolution`, `physical memory mapping`, `process address-space attach`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmGetPhysicalAddress`, `MmMapIoSpaceEx`, `MmProbeAndLockPages`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
