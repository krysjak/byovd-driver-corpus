# `mssecflt.sys`

[Назад до індексу](../README.uk.md) · [English version](mssecflt.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `533E27657B78A1B2DDA5A9AAD71B04D5297FE4F61F55463F6CA53B355B9C923C` | `E1005DBF33808BAD37FBC7F22C3A9D60BF35AFBB` | `5A6719636FEABA346294201526606208` |

## Метадані

- **Ім'я файлу:** `mssecflt.sys`
- **Розмір:** 392680 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Microsoft Security Events Component file system filter driver
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** —
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `arbitrary memory copy`, `process address-space attach`, `process lookup`

**Imports:** `KeStackAttachProcess`, `MmCopyMemory`, `PsLookupProcessByProcessId`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
