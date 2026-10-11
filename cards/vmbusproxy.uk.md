# `vmbusproxy.sys`

[Назад до індексу](../README.uk.md) · [English version](vmbusproxy.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `10915CBC92DE7B95CCDC79CB6A9AA96B4F0190BC8B291F75FA47D78ABCADBDCA` | `7C9BC578F4CD789D2BF05F727B5EA1C2FF1BC988` | `0EB834AAE61D88250DC42F2BEAA9D973` |

## Метадані

- **Ім'я файлу:** `vmbusproxy.sys`
- **Розмір:** 98304 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Microsoft Hyper-V VMBus Proxy Driver
- **Підпис:** unsigned
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `process address-space attach`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
