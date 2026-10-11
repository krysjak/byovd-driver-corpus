# `rdbss.sys`

[Назад до індексу](../README.uk.md) · [English version](rdbss.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `6817A01FAA09F7CF11F6745DA584CC5667A4616522744B78E6A3D77559E57F48` | `E0F56A8C42A8DF847837767135BF8A7CF0F68DF7` | `B7AFAFFF83CCCD6405AEAB733D606E44` |

## Метадані

- **Ім'я файлу:** `rdbss.sys`
- **Розмір:** 566760 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Redirected Drive Buffering SubSystem Driver
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** —
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `page locking`, `process address-space attach`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmProbeAndLockPages`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
