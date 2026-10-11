# `rfcomm.sys`

[Назад до індексу](../README.uk.md) · [English version](rfcomm.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `A5E9B12EBAAFDA10B2BE4610B5618DBFD568AF4276A1C780AA4B4B6A208CB2ED` | `84C3E0ECB1E2E9F6732015846889AD461031D17B` | `856F80DC85931317D7C454F21C0B6650` |

## Метадані

- **Ім'я файлу:** `rfcomm.sys` (Ідентичні копії: `rfcomm_1.sys`)
- **Розмір:** 253952 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Bluetooth RFCOMM Driver
- **Підпис:** unsigned
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `process lookup`

**Imports:** `IoAllocateMdl`, `PsLookupProcessByProcessId`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
