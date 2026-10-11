# `WdDevFlt.sys`

[Назад до індексу](../README.uk.md) · [English version](WdDevFlt.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `EB67997A44E13DD4B6E628BD6941E956E39D9198467539C5864C92CDDACA2828` | `C83957E8D26473A6AA8F95259F1E1E5BA4056EC3` | `B6F08FE8A3756673A93AF46DE2D97B34` |

## Метадані

- **Ім'я файлу:** `WdDevFlt.sys`
- **Розмір:** 300424 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Microsoft antimalware device filter driver
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** —
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `process handle access`, `process lookup`

**Imports:** `PsLookupProcessByProcessId`, `ZwOpenProcess`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
