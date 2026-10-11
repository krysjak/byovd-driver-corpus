# `condrv.sys`

[Назад до індексу](../README.uk.md) · [English version](condrv.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `3B424955065267757DD33A3B04836D7853A5345E67E8D11CEEDF6CCD064095B9` | `4B5774BB739AFDDF8232EFAD98692E99FA9B57BE` | `6F8988BC8542FA477966BCE94DDE8FED` |

## Метадані

- **Ім'я файлу:** `condrv.sys`
- **Розмір:** 91440 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Console Driver
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** — · **Немає перевірки probe:** —
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `page locking`, `process address-space attach`, `process handle access`, `process termination`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmProbeAndLockPages`, `ZwOpenProcess`, `ZwTerminateProcess`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
