# `ApxUnit.sys`

[Назад до індексу](../README.uk.md) · [English version](ApxUnit.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `64111384E06C6989F7FF8D1E1D938EC97A085493B88819C1BA4AAA6550BB44A9` | `D4E793138159CF3653B84F0A9E798D2397673E8C` | `CF2D004B6808666DA203D61674DFCE72` |

## Метадані

- **Ім'я файлу:** `ApxUnit.sys`
- **Розмір:** 155648 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Audio Kernel-Mode Proxy Unit Driver
- **Підпис:** unsigned
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `process address-space attach`, `process handle access`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `ZwOpenProcess`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
