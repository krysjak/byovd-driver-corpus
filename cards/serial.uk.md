# `serial.sys`

[Назад до індексу](../README.uk.md) · [English version](serial.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `0CCE651E05C888A994C4370233E0F68ECE99821E652CF075EA389A1B8F62515F` | `339FB97840C87F6A52F3E560CBE0DC6D630AF064` | `FC96CAFDDA51408494B3F68A21B7F05E` |

## Метадані

- **Ім'я файлу:** `serial.sys` (Ідентичні копії: `serial_1.sys`)
- **Розмір:** 122880 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Serial Device Driver
- **Підпис:** unsigned
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `physical address resolution`, `physical memory mapping`

**Imports:** `MmGetPhysicalAddress`, `MmMapIoSpaceEx`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
