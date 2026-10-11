# `netbios.sys`

[Назад до індексу](../README.uk.md) · [English version](netbios.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `29C10B2BD9C7272C7C71462F39252A75DE0159ECCFC58BDF1C407D8C226F0AFC` | `EC099BA1625A5DC0667EA1D8AC8598B9A6D97355` | `DCB8D72D796A8F7B4173F8C378EE39EF` |

## Метадані

- **Ім'я файлу:** `netbios.sys`
- **Розмір:** 99632 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** NetBIOS interface driver
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** — · **Немає перевірки probe:** —
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `page locking`, `process address-space attach`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmProbeAndLockPages`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
