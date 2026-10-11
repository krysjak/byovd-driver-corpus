# `winhv.sys`

[Назад до індексу](../README.uk.md) · [English version](winhv.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `DF2020BE376215D828C809D1C1D44FEDEC778CABE18C71E5E2E9F6AE92B5668E` | `A55EDF5FFBA9A8D06D65B29E603A11975BF80C88` | `B0DBDE1F92183ACA0058AC09EA12C31C` |

## Метадані

- **Ім'я файлу:** `winhv.sys`
- **Розмір:** 75248 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Windows Hypervisor Interface Driver
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `physical address resolution`, `physical memory mapping`, `system information set`

**Imports:** `MmGetPhysicalAddress`, `MmMapIoSpaceEx`, `ZwSetSystemInformation`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
