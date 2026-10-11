# `BasicRender.sys`

[Назад до індексу](../README.uk.md) · [English version](BasicRender.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `CBAC7C00AC64C28FA56B735AB4065C9D95FCB992F84B00100309F8737DAA819D` | `5BD4FBD608CD1EDE801045B2BB87297B540A8CDE` | `62E82D0E4C5E72546747A0C97612509A` |

## Метадані

- **Ім'я файлу:** `BasicRender.sys`
- **Розмір:** 73728 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Microsoft Basic Render Driver
- **Підпис:** unsigned
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** —
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `driver loading`, `page locking`, `physical address resolution`, `process address-space attach`, `process handle access`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmGetPhysicalAddress`, `MmProbeAndLockPages`, `ZwLoadDriver`, `ZwOpenProcess`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
