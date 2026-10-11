# `VerifierExt.sys`

[Назад до індексу](../README.uk.md) · [English version](VerifierExt.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `D2FCAC287E70B20D32762728770A7BF3EA7970C1C8C1C317A7B3F93C9200542B` | `8F617EFFFA4A1E66FAB82A8B9A575283238B61EF` | `B0001C4C55DF526FF5D20B3EE442D9F2` |

## Метадані

- **Ім'я файлу:** `VerifierExt.sys`
- **Розмір:** 271848 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Driver Verifier Extension
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `page locking`

**Imports:** `IoAllocateMdl`, `MmProbeAndLockPages`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
