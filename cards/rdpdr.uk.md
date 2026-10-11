# `rdpdr.sys`

[Назад до індексу](../README.uk.md) · [English version](rdpdr.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `44176316C7F66C945D44AF6A9274DCD6C5FB9D71766B9D6B3B60F2533DD38FAD` | `8C19712BB73A7BF7768D504BBCB5672B9ECA7786` | `524B8A2152A47FBA31060262026BBEB1` |

## Метадані

- **Ім'я файлу:** `rdpdr.sys`
- **Розмір:** 212992 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Microsoft RDP Device redirector
- **Підпис:** unsigned
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** —
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `page locking`, `process lookup`

**Imports:** `IoAllocateMdl`, `MmProbeAndLockPages`, `PsLookupProcessByProcessId`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
