# `igdkmdnd64_7.sys`

[Назад до індексу](../README.uk.md) · [English version](igdkmdnd64_7.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `4E6EDE376C864F76577CE7455DFE71D2654B3A39951CC931028A440CF678D4BB` | `A5E3C9D8E6864D04561141FC0406F5FBFDCD5F58` | `0B7552DC293A83EB4B2F22C993DC8A25` |

## Метадані

- **Ім'я файлу:** `igdkmdnd64_7.sys`
- **Розмір:** 40284216 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel HD Graphics Drivers for Windows(R)
- **Опис:** Intel Graphics Kernel Mode New Driver
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** —
- **У системах:** OEM package
- **Score:** 160

## Профіль можливостей

**Primitives:** `MDL allocation`, `driver loading`, `page locking`, `physical address resolution`, `physical memory mapping`, `process address-space attach`, `process handle access`, `process lookup`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmGetPhysicalAddress`, `MmMapIoSpace`, `MmMapIoSpaceEx`, `MmProbeAndLockPages`, `PsLookupProcessByProcessId`, `ZwLoadDriver`, `ZwOpenProcess`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
