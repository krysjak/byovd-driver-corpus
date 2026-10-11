# `WUDFPf.sys`

[Назад до індексу](../README.uk.md) · [English version](WUDFPf.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `5E46ACA0C46B2662BC3E4FD0B68C70BB4E6F00A80FD107BA731435981667FA45` | `A5E07D69772E8330E24934C3E7C118B7516E91F3` | `8018D2073EF8D4B8A1F820DC047731E4` |

## Метадані

- **Ім'я файлу:** `WUDFPf.sys`
- **Розмір:** 173520 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Windows Driver Foundation - User-mode Driver Framework Platform Driver
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `process address-space attach`, `process handle access`, `process termination`

**Imports:** `KeStackAttachProcess`, `ZwOpenProcess`, `ZwTerminateProcess`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
