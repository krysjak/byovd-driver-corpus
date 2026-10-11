# `pcw.sys`

[Назад до індексу](../README.uk.md) · [English version](pcw.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `B6C09B56EA59B7A63D1E77EC982A9EFA2E9F381DBEF461F490AFC0037D1C24B8` | `8E99D0A021C23C8DE7A2310E970546D9EB6C429E` | `86ADF9B97A3C7ED2A954531EEF715397` |

## Метадані

- **Ім'я файлу:** `pcw.sys`
- **Розмір:** 103896 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Performance Counters for Windows Driver
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** — · **Немає перевірки probe:** —
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `cross-process memory copy`, `process address-space attach`

**Imports:** `KeStackAttachProcess`, `MmCopyVirtualMemory`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
