# `dxgkrnl.sys`

[Назад до індексу](../README.uk.md) · [English version](dxgkrnl.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `8F57DD6EFDCE62637075629C711A4D376ECBD7C77B09B0F82F5C261B3EE41358` | `D58273D48BEE7D1EFA7368F4E41C5777D7E96353` | `7325C5EF71355B40DB8137BFC2340E08` |

## Метадані

- **Ім'я файлу:** `dxgkrnl.sys`
- **Розмір:** 5207584 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** DirectX Graphics Kernel
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** —
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `contiguous physical allocation`, `page locking`, `physical address resolution`, `physical memory mapping`, `process address-space attach`, `process handle access`, `process lookup`, `process termination`, `section mapping (kernel R/W surface)`, `section object access`, `system information set`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmAllocateContiguousMemory`, `MmGetPhysicalAddress`, `MmMapIoSpaceEx`, `MmProbeAndLockPages`, `PsLookupProcessByProcessId`, `ZwMapViewOfSection`, `ZwOpenProcess`, `ZwOpenSection`, `ZwSetSystemInformation`, `ZwTerminateProcess`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
