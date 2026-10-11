# `amdkmdag_1.sys`

[Назад до індексу](../README.uk.md) · [English version](amdkmdag_1.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `2D2A7F31472CE760D9D10ED74DB7622827AFBC4E08AB98A918F3358B7DD26A9B` | `CDE47BB8F1E3CB7AE3856192713CDC0F48F16112` | `66DC4F37F841B8C3540C072AFCB2E790` |

## Метадані

- **Ім'я файлу:** `amdkmdag_1.sys`
- **Розмір:** 106012248 bytes
- **Архітектура:** 0x8664
- **Компанія:** Advanced Micro Devices, Inc.
- **Продукт:** ATI Radeon Family
- **Опис:** ATI Radeon Kernel Mode Driver
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** — · **Немає перевірки probe:** —
- **У системах:** OEM package
- **Score:** 165

## Профіль можливостей

**Primitives:** `MDL allocation`, `driver loading`, `page locking`, `physical address resolution`, `physical memory mapping`, `process address-space attach`, `process handle access`, `process lookup`, `process termination`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmGetPhysicalAddress`, `MmMapIoSpace`, `MmProbeAndLockPages`, `PsLookupProcessByProcessId`, `ZwLoadDriver`, `ZwOpenProcess`, `ZwTerminateProcess`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
