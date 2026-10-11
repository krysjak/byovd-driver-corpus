# `HttpDebuggerSdk.sys`

[Назад до індексу](../README.uk.md) · [English version](HttpDebuggerSdk.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `2E89606775ED719B9D950AE9D37E819A2567426FBE5C3E0AAD8D86FEC693B67B` | `5266036308E0D0EB837CC3126DBA5A0B6EC270FC` | `947C624C4BD48F8C66FCD00FC0F947D4` |

## Метадані

- **Ім'я файлу:** `HttpDebuggerSdk.sys`
- **Розмір:** 100136 bytes
- **Архітектура:** 0x8664
- **Компанія:** Windows (R) Win 7 DDK provider
- **Продукт:** Windows (R) Win 7 DDK driver
- **Опис:** NetFilter SDK WFP Driver (WPP)
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
