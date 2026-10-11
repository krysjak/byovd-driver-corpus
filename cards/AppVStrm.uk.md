# `AppVStrm.sys`

[Назад до індексу](../README.uk.md) · [English version](AppVStrm.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `3A3E7226604BBB69EDE8BC8A4FDE61F59922B8C795442D7F05A8077C11A2FA0C` | `6E4B1411D8E3D91D72CE2C55C3589801511DD567` | `C7415379FB9F8DE40CCCC1E9162002FE` |

## Метадані

- **Ім'я файлу:** `AppVStrm.sys`
- **Розмір:** 177456 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Microsoft Application Virtualization Streaming Driver
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** —
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `page locking`, `process address-space attach`, `process handle access`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmProbeAndLockPages`, `ZwOpenProcess`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
