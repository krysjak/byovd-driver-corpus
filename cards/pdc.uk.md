# `pdc.sys`

[Назад до індексу](../README.uk.md) · [English version](pdc.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `83487A10400C635328957D47A5F43540E971C9328A83D46455391AF3A5C6838C` | `4A2BF68DAD8F79071A84ED1AC74EF725628F9DD3` | `CFE716E7843009AE733BFE3748C0651C` |

## Метадані

- **Ім'я файлу:** `pdc.sys`
- **Розмір:** 214504 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Power Dependency Coordinator Driver
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `process address-space attach`, `process handle access`, `process lookup`

**Imports:** `KeStackAttachProcess`, `PsLookupProcessByProcessId`, `ZwOpenProcess`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
