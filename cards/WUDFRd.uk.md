# `WUDFRd.sys`

[Назад до індексу](../README.uk.md) · [English version](WUDFRd.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `989F0C323E826653BFA0F3DD6EEB72621D7DF75BC0FA1C6DDFB5229431C39B0B` | `7FD1773780833D424926036A4F1BDA88A687D15E` | `910F0109DC99FFC11725688ECFC64545` |

## Метадані

- **Ім'я файлу:** `WUDFRd.sys`
- **Розмір:** 411096 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Windows Driver Foundation - User-mode Driver Framework Reflector
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** —
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `page locking`, `physical memory mapping`, `process address-space attach`, `process handle access`, `process termination`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmMapIoSpaceEx`, `MmProbeAndLockPages`, `ZwOpenProcess`, `ZwTerminateProcess`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
