# `amdfendr.sys`

[Назад до індексу](../README.uk.md) · [English version](amdfendr.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `145BE5CFBC40DA8DB78C2AC4DAF921B00ADB27B62072B58B13794C229FDFB758` | `0088E9A1877F4AF91BE0E16D63021CEAE846439C` | `7AA87C1737A3F707586050304CCE6B91` |

## Метадані

- **Ім'я файлу:** `amdfendr.sys`
- **Розмір:** 375192 bytes
- **Архітектура:** 0x8664
- **Компанія:** Advanced Micro Devices, Inc.
- **Продукт:** AMD Driver
- **Опис:** AMD Crash Defender
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmMapIoSpace`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
