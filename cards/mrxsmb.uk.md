# `mrxsmb.sys`

[Назад до індексу](../README.uk.md) · [English version](mrxsmb.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `A0EDBE066A3D52BF0134E7D76A757102617D1CABFEE5C0CC5E6CE9125FB0FD7A` | `F375C5E7C4D5FCF5E6E20C55E934E23DB6002422` | `C597717DE2519BD95571412A12E354DE` |

## Метадані

- **Ім'я файлу:** `mrxsmb.sys`
- **Розмір:** 943616 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Windows NT SMB Minirdr
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** —
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `driver loading`, `page locking`, `process address-space attach`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmProbeAndLockPages`, `ZwLoadDriver`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
