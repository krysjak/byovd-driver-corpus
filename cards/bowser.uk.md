# `bowser.sys`

[Назад до індексу](../README.uk.md) · [English version](bowser.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `7B30D7F70DEACDC84338EFF05212C099F412815A5FD64BB4B9EFC293C52C69C3` | `F66AD475742614DFF35560FE4D6A6CA218A6D540` | `B05E990F19C541460F3CE2BE093309AD` |

## Метадані

- **Ім'я файлу:** `bowser.sys`
- **Розмір:** 163840 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** NT Lan Manager Datagram Receiver Driver
- **Підпис:** unsigned
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** — · **Немає перевірки probe:** —
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `page locking`, `process address-space attach`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmProbeAndLockPages`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
