# `srvnet.sys`

[Назад до індексу](../README.uk.md) · [English version](srvnet.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `D6A74DECFD0F11FB6FFB4CACB157F6345EF5514B1DBC3B4102363F6EBCFEF9BB` | `471689E84636731AD2A18863C9F7DA33ADB5B328` | `E6C8BC3F3195298735D82BA2B083B29F` |

## Метадані

- **Ім'я файлу:** `srvnet.sys`
- **Розмір:** 405504 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Server Network driver
- **Підпис:** unsigned
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** — · **Немає перевірки probe:** —
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `driver loading`, `page locking`, `process address-space attach`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmProbeAndLockPages`, `ZwLoadDriver`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
