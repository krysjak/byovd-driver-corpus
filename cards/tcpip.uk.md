# `tcpip.sys`

[Назад до індексу](../README.uk.md) · [English version](tcpip.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `15034904B98C49B959C848F48ADA109E86F6EE97BA5422FF9A6A61D848C6AF39` | `5DA4FD9E08F97B78A37C367134B251FC02A8C8D8` | `CF88CBCD74AF47D7C98F99F4D9A7BA4E` |

## Метадані

- **Ім'я файлу:** `tcpip.sys`
- **Розмір:** 3474920 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** TCP/IP Driver
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `page locking`, `process address-space attach`, `process handle access`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmProbeAndLockPages`, `ZwOpenProcess`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
