# `Vid.sys`

[Назад до індексу](../README.uk.md) · [English version](Vid.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `0E4A4E121BFF67928BDB23241CA21A7594241E45BF4F9D8C560754868ECA4B57` | `4B0AA20CC077D46886A706159D4528A2CABCCF8E` | `4067EDB06E47E82388E91A3843210BA8` |

## Метадані

- **Ім'я файлу:** `Vid.sys` (Ідентичні копії: `Vid_1.sys`)
- **Розмір:** 910816 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Microsoft Hyper-V Virtualization Infrastructure Driver
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** —
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `cross-process memory copy`, `page locking`, `physical memory mapping`, `process address-space attach`, `process termination`, `section object access`, `system information set`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmCopyVirtualMemory`, `MmMapIoSpaceEx`, `MmProbeAndLockPages`, `ZwOpenSection`, `ZwSetSystemInformation`, `ZwTerminateProcess`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
