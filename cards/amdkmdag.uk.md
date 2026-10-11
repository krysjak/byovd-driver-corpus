# `amdkmdag.sys`

[Назад до індексу](../README.uk.md) · [English version](amdkmdag.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `8E55DC86A58D07E4AF756B5CAD8E3B14594ADC280395F0F15D207E4124E9549C` | `D1E3BB1ADD7D5D5C8DD728B534D9FFEAE85537DF` | `DD2937EAB5A94D5C36AA74D1E755F58F` |

## Метадані

- **Ім'я файлу:** `amdkmdag.sys`
- **Розмір:** 102145040 bytes
- **Архітектура:** 0x8664
- **Компанія:** Advanced Micro Devices, Inc.
- **Продукт:** ATI Radeon Family
- **Опис:** ATI Radeon Kernel Mode Driver
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** — · **Немає перевірки probe:** —
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `driver loading`, `page locking`, `physical address resolution`, `physical memory mapping`, `process address-space attach`, `process handle access`, `process lookup`, `process termination`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmGetPhysicalAddress`, `MmMapIoSpace`, `MmProbeAndLockPages`, `PsLookupProcessByProcessId`, `ZwLoadDriver`, `ZwOpenProcess`, `ZwTerminateProcess`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
