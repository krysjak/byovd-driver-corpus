# `dam.sys`

[Назад до індексу](../README.uk.md) · [English version](dam.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `256DE6D4F79F0CCA6FFFA158C6CDD97F1FE53F35A89BA73FB25B46F647E1592D` | `6AB7281F5D1873F2B48F87397A6EE7D6790B3480` | `D38F44ED72B71F923E0A8AE518260B4F` |

## Метадані

- **Ім'я файлу:** `dam.sys`
- **Розмір:** 136664 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** DAM Kernel Driver
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `process handle access`, `process lookup`

**Imports:** `PsLookupProcessByProcessId`, `ZwOpenProcess`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
