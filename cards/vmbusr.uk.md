# `vmbusr.sys`

[Назад до індексу](../README.uk.md) · [English version](vmbusr.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `CA94C3A93E311E742ADBD2480212A03F6A5FF83B9BA448659EA42C32AA93DC8A` | `C3CBA4B84432C882E35814521805A5751C31AD45` | `A3B1D666C76A726325CF3CBDF5E04B2F` |

## Метадані

- **Ім'я файлу:** `vmbusr.sys` (Ідентичні копії: `vmbusr_1.sys`)
- **Розмір:** 316904 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Microsoft Hyper-V Virtual Machine Bus Root Driver
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `page locking`, `physical address resolution`, `process address-space attach`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmGetPhysicalAddress`, `MmProbeAndLockPages`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
