# `gnf.sys`

[Назад до індексу](../README.uk.md) · [English version](gnf.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `4A406C7CFAE7C320F58666BAB8A47D1801DD7CCFC8834A183A5E2F3905442DE9` | `9FA778C41746F1D0D10AEF7526B97C68127CC886` | `0153A075648EBCD347BA87F8649CA51A` |

## Метадані

- **Ім'я файлу:** `gnf.sys`
- **Розмір:** 102416 bytes
- **Архітектура:** 0x8664
- **Компанія:** Windows (R) Win 7 DDK provider
- **Продукт:** GTB Extreme Network Driver
- **Опис:** GTB Extreme Network Driver
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
