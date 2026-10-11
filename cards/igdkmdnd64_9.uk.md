# `igdkmdnd64_9.sys`

[Назад до індексу](../README.uk.md) · [English version](igdkmdnd64_9.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `EF95B766A178943D408B9AE9ECF686CEA8288BB88948086995ACC895CC81891E` | `E190830CF9C7F83C0F1622B77AD4059A68229EB9` | `83F531AB10D55A6FA0E2A932725DB900` |

## Метадані

- **Ім'я файлу:** `igdkmdnd64_9.sys`
- **Розмір:** 28658752 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel HD Graphics Drivers for Windows(R)
- **Опис:** Intel Graphics Kernel Mode New Driver
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** —
- **У системах:** OEM package
- **Score:** 130

## Профіль можливостей

**Primitives:** `MDL allocation`, `driver loading`, `page locking`, `physical address resolution`, `physical memory mapping`, `process address-space attach`, `process handle access`, `process lookup`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmGetPhysicalAddress`, `MmMapIoSpace`, `MmProbeAndLockPages`, `PsLookupProcessByProcessId`, `ZwLoadDriver`, `ZwOpenProcess`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
