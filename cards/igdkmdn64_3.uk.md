# `igdkmdn64_3.sys`

[Назад до індексу](../README.uk.md) · [English version](igdkmdn64_3.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `9081A461469BCC71A72184DB7665F532030D9510564AC8F10473BBE36237E724` | `7EA0C0998938291898C0B5F9443CE3323F06B001` | `C5143248F5A26E76ADAA68E048797DD2` |

## Метадані

- **Ім'я файлу:** `igdkmdn64_3.sys`
- **Розмір:** 53115072 bytes
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
