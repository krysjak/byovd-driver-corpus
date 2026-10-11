# `ApxUnit_1.sys`

[Назад до індексу](../README.uk.md) · [English version](ApxUnit_1.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `73435C52CAF5DEE2C42A21AE0BC8EFAE386268A19913C43511C676647BD8BEAD` | `C8D64C2340B5441920A937FFAB653B4ABC936CAB` | `39731300EEAD994AF57EB3597DF09086` |

## Метадані

- **Ім'я файлу:** `ApxUnit_1.sys` (Ідентичні копії: `ApxUnit_2.sys`)
- **Розмір:** 163840 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Audio Kernel-Mode Proxy Unit Driver
- **Підпис:** unsigned
- **Джерело:** `local`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Live system
- **Score:** 50

## Профіль можливостей

**Primitives:** `MDL allocation`, `process address-space attach`, `process handle access`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `ZwOpenProcess`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
