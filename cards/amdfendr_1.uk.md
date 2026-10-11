# `amdfendr_1.sys`

[Назад до індексу](../README.uk.md) · [English version](amdfendr_1.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `28ED50420493AAAB06D74159F795788B0B5AB9107E247597C8A4629B214DBBF7` | `E8BD8B951B6FEDE2DBCFA3AD16D26D7DE6AE4E72` | `978D3CD0BE776BCB84B0AB742F023A63` |

## Метадані

- **Ім'я файлу:** `amdfendr_1.sys`
- **Розмір:** 367312 bytes
- **Архітектура:** 0x8664
- **Компанія:** Advanced Micro Devices, Inc.
- **Продукт:** AMD Driver
- **Опис:** AMD Crash Defender
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 100

## Профіль можливостей

**Primitives:** `MDL allocation`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmMapIoSpace`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
