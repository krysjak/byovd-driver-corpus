# `stream.sys`

[Назад до індексу](../README.uk.md) · [English version](stream.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `C162F0DC9EECA81D13243747A35196F7F8F0DC1C316E9B88AF8A0F6CD5EEE6FA` | `1F231A3146D8BA4E181C17621F58233B4B7F7BFC` | `35F5FAEBECFE4646D966D23AB1D74052` |

## Метадані

- **Ім'я файлу:** `stream.sys`
- **Розмір:** 118784 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** WDM CODEC Class Device Driver 2.0
- **Підпис:** unsigned
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** — · **Немає перевірки probe:** —
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmMapIoSpaceEx`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
