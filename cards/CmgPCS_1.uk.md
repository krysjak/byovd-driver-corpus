# `CmgPCS_1.sys`

[Назад до індексу](../README.uk.md) · [English version](CmgPCS_1.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `4DD31A1972C2FD4DDFDB2CFAD916603DE4EF9D2179827F55847FA1A24B0E4E62` | `58F362D582E908D0277F5F2F077923B418AA7201` | `DF960F98D039CCD7BF13872A36640FFD` |

## Метадані

- **Ім'я файлу:** `CmgPCS_1.sys`
- **Розмір:** 159456 bytes
- **Архітектура:** 0x8664
- **Компанія:** Dell Inc.
- **Продукт:** CmgPCS.sys (64b,rls)
- **Опис:** Port Controls Driver
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 110

## Профіль можливостей

**Primitives:** `MDL allocation`, `page locking`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmMapIoSpace`, `MmProbeAndLockPages`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
