# `cdfs.sys`

[Назад до індексу](../README.uk.md) · [English version](cdfs.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `C6EE866166E1019C5D9560E2C34AA4203D0C40FCB8EAC50C5A31223C08A0C334` | `BE14A53B8A83A2E837D1E3054CDA15E076C31F5D` | `7343300029A25828E41B5E37279F62E7` |

## Метадані

- **Ім'я файлу:** `cdfs.sys`
- **Розмір:** 131072 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** CD-ROM File System Driver
- **Підпис:** unsigned
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `page locking`

**Imports:** `IoAllocateMdl`, `MmProbeAndLockPages`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
