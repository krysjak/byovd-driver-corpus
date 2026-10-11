# `cldflt.sys`

[Назад до індексу](../README.uk.md) · [English version](cldflt.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `AA4FABFA1BEDC600AD52F7124EDFE6896A337B4D6478840F62C0EA890477E4D9` | `B9055B606A9BA93C589221A3891EE00250A0F16A` | `8D1403963E4BB426961E8AF3DC024180` |

## Метадані

- **Ім'я файлу:** `cldflt.sys`
- **Розмір:** 602112 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Cloud Files Mini Filter Driver
- **Підпис:** unsigned
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** — · **Немає перевірки probe:** —
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `page locking`, `process address-space attach`, `process handle access`, `process lookup`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmProbeAndLockPages`, `PsLookupProcessByProcessId`, `ZwOpenProcess`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
