# `nvmedisk.sys`

[Назад до індексу](../README.uk.md) · [English version](nvmedisk.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `ED789955358FEB3D5E7FAA3BB46E6CF69656774DBC73F61328F4071347F5724D` | `D657DFCDDC0EBC766769A3A499545B11DF2D80B1` | `6A4CD2563CDE071A97A2E3862AF62CCE` |

## Метадані

- **Ім'я файлу:** `nvmedisk.sys` (Ідентичні копії: `nvmedisk_1.sys`)
- **Розмір:** 128488 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Nvme Disk Driver
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `page locking`, `physical address resolution`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmProbeAndLockPages`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
