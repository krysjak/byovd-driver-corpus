# `AppvVemgr.sys`

[Назад до індексу](../README.uk.md) · [English version](AppvVemgr.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `C8BCD77030F948A6287ADDA728FCBA6B4297DEC9FE6A05CDECCEF624075C8AE1` | `A90FB6E87B9A7F2BD39FB6B267CFFF4A84259674` | `633A321028E777F0F5A9F055559F34EA` |

## Метадані

- **Ім'я файлу:** `AppvVemgr.sys`
- **Розмір:** 218432 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Microsoft Application Virtualization VE Manager Driver
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `process handle access`, `process termination`

**Imports:** `ZwOpenProcess`, `ZwTerminateProcess`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
