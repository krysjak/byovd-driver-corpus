# `flpydisk.sys`

[Назад до індексу](../README.uk.md) · [English version](flpydisk.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `2B920DCEDB85453F619C599083046B6DE8670886AB2D13593771DFADCCEBBEB2` | `7989EAAE9A4BD54D374CD7D4E213ED33528FA4B8` | `27FDBA8F9DC034A82735E6F28768377C` |

## Метадані

- **Ім'я файлу:** `flpydisk.sys` (Ідентичні копії: `flpydisk_1.sys`)
- **Розмір:** 65536 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Floppy Driver
- **Підпис:** unsigned
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
