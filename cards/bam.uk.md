# `bam.sys`

[Назад до індексу](../README.uk.md) · [English version](bam.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `9FC71FF6494CCE9A89EB224864E57371B6527227022137DA3C608B10C36EFA5D` | `9E5C5499AD2A351DFEB171FA8F520FF4A2FE900F` | `F9F24468A3001A923A2631269A49288E` |

## Метадані

- **Ім'я файлу:** `bam.sys`
- **Розмір:** 124400 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** BAM Kernel Driver
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `process lookup`

**Imports:** `PsLookupProcessByProcessId`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
