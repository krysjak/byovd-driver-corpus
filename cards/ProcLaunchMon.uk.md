# `ProcLaunchMon.sys`

[Назад до індексу](../README.uk.md) · [English version](ProcLaunchMon.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `3FCAC4371460EF510BEA9D772FFAD68D2AF0720078AC3BD84BD1E4979CF882E4` | `38C9C7127A50B6A360828F75A7D9815E17F84294` | `B61E3C79123E8589568111F7D9199FA7` |

## Метадані

- **Ім'я файлу:** `ProcLaunchMon.sys`
- **Розмір:** 79880 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Time Travel Debugging Process Launch Monitor driver
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `process handle access`

**Imports:** `ZwOpenProcess`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
