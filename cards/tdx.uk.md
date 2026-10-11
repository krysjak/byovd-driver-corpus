# `tdx.sys`

[Назад до індексу](../README.uk.md) · [English version](tdx.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `3E221BD24B0D171812EB354A73DEDC209F7CB3DACB78523D3F0651352269ACCF` | `93587F253B32CD1A938056FF25550F170A40000C` | `B5D8C4A0944224F9FFBE55082CACCF27` |

## Метадані

- **Ім'я файлу:** `tdx.sys`
- **Розмір:** 181712 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** TDI Translation Driver
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** —
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `page locking`

**Imports:** `IoAllocateMdl`, `MmProbeAndLockPages`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
