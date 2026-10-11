# `igdkmdn64_4.sys`

[Назад до індексу](../README.uk.md) · [English version](igdkmdn64_4.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `38C3CE6C5FBAEC4C4B77777091C4A4E16A41C19882DD1B3F7CFF817EB316E0CB` | `815A5F710A02113BF21B0CFB550DA53A232E329C` | `D0BB6FE2C7AD1E986BE498C270019C25` |

## Метадані

- **Ім'я файлу:** `igdkmdn64_4.sys`
- **Розмір:** 54575312 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel HD Graphics Drivers for Windows(R)
- **Опис:** Intel Graphics Kernel Mode New Driver
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** —
- **У системах:** OEM package
- **Score:** 180

## Профіль можливостей

**Primitives:** `MDL allocation`, `arbitrary memory copy`, `driver loading`, `page locking`, `physical address resolution`, `physical memory mapping`, `process address-space attach`, `process handle access`, `process lookup`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmCopyMemory`, `MmGetPhysicalAddress`, `MmMapIoSpace`, `MmMapIoSpaceEx`, `MmProbeAndLockPages`, `PsLookupProcessByProcessId`, `ZwLoadDriver`, `ZwOpenProcess`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
