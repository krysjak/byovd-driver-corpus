# `Vid_2.sys`

[Назад до індексу](../README.uk.md) · [English version](Vid_2.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `7F90AADC25CA83DED17A3DE262A64C6DEFD6EE6E50C5ED71F86F7D0B9CC3AC91` | `5D85BD805F7B818343BCD7C225F7C36D82E9A058` | `F6B66498AC898D43B083576B411529EB` |

## Метадані

- **Ім'я файлу:** `Vid_2.sys` (Ідентичні копії: `Vid_3.sys`)
- **Розмір:** 914840 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Microsoft Hyper-V Virtualization Infrastructure Driver
- **Підпис:** signed
- **Джерело:** `local`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** —
- **У системах:** Live system
- **Score:** 155

## Профіль можливостей

**Primitives:** `MDL allocation`, `cross-process memory copy`, `page locking`, `physical memory mapping`, `process address-space attach`, `process termination`, `section object access`, `system information set`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmCopyVirtualMemory`, `MmMapIoSpaceEx`, `MmProbeAndLockPages`, `ZwOpenSection`, `ZwSetSystemInformation`, `ZwTerminateProcess`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
