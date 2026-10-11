# `rmcast.sys`

[Назад до індексу](../README.uk.md) · [English version](rmcast.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `8D8463382D7D33B129F8F428E93FFEC05721B631D5F4BA1131086ADBC16679A9` | `041EF755F0750AF7B7DC808C644EB63A343074AC` | `D69D9CB54A62D1541E5D3A67CE1E75EC` |

## Метадані

- **Ім'я файлу:** `rmcast.sys`
- **Розмір:** 200704 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Reliable Multicast Transport
- **Підпис:** unsigned
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `page locking`, `process address-space attach`, `section mapping (kernel R/W surface)`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmProbeAndLockPages`, `ZwMapViewOfSection`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
