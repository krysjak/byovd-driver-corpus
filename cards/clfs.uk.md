# `clfs.sys`

[Назад до індексу](../README.uk.md) · [English version](clfs.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `5880C90802C71110794D4BE2552225B9D7784ECAE63DF144AE0177C11F35546C` | `C67DD28721423F455CC96E224257AF30E7D78D15` | `DCF5EC0612E12FE01201C66C3E6A7D31` |

## Метадані

- **Ім'я файлу:** `clfs.sys`
- **Розмір:** 570840 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Common Log File System Driver
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
