# `WdNisDrv.sys`

[Назад до індексу](../README.uk.md) · [English version](WdNisDrv.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `66A19E397D0709556CEF79886CA8562329ACEDCE7B6F63970A61953E566B3D25` | `78790D7357EA894FD4067F6468FFD9624DA6545E` | `168B3BB22E48AC4FF592BDEE8CEF5D22` |

## Метадані

- **Ім'я файлу:** `WdNisDrv.sys`
- **Розмір:** 103816 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Windows Defender Network Stream Filter
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `process lookup`

**Imports:** `IoAllocateMdl`, `PsLookupProcessByProcessId`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
