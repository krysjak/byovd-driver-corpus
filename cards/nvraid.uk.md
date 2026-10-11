# `nvraid.sys`

[Назад до індексу](../README.uk.md) · [English version](nvraid.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `DB769BF751D7B23FFCE8CC1BAABB335DA5DA15E06A845A049EB68C3791686FED` | `76772B44ABB64BB9437307E354A62AA83FB6201F` | `FB6829DFAE5EA01864C3CFE35452F7E3` |

## Метадані

- **Ім'я файлу:** `nvraid.sys` (Ідентичні копії: `nvraid_1.sys`)
- **Розмір:** 151472 bytes
- **Архітектура:** 0x8664
- **Компанія:** NVIDIA Corporation
- **Продукт:** NVIDIA nForce(TM) RAID Driver
- **Опис:** NVIDIA® nForce(TM) RAID Driver
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `page locking`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmMapIoSpace`, `MmProbeAndLockPages`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
