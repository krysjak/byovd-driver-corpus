# `ksecdd.sys`

[Назад до індексу](../README.uk.md) · [English version](ksecdd.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `BA475FB8990CAA50DA5E8C53EF3FD2175FFE4EF2813341916082A66EC8118750` | `A5043B1A6EA65F27356A04963FA612795B85542A` | `9AB724A176D87551702B94FEFB2071E8` |

## Метадані

- **Ім'я файлу:** `ksecdd.sys`
- **Розмір:** 230888 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Kernel Security Support Provider Interface
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** — · **Немає перевірки probe:** —
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `cross-process memory copy`

**Imports:** `MmCopyVirtualMemory`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
