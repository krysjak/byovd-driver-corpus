# `crashdmp.sys`

[Назад до індексу](../README.uk.md) · [English version](crashdmp.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `25698C7ADCBB3B0413D7D58E0355D828C48FE2C8F673040F7372382AF4A6ED53` | `6D7A09C67D5E64C3F9F3DA03462E627BAF9CF69F` | `68619CFB0D944864B555A9CC52A5E217` |

## Метадані

- **Ім'я файлу:** `crashdmp.sys`
- **Розмір:** 161272 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Crash Dump Driver
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `physical address resolution`, `system information set`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `ZwSetSystemInformation`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
