# `igdkmdnd64_4.sys`

[Назад до індексу](../README.uk.md) · [English version](igdkmdnd64_4.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `C7535C20E06B230D0292B2A5B92FE3E5D653F3E72A54D904727C1652ADD759EE` | `970F0C5E2E3760CC42DCB709BB2BCC77C74C726D` | `D1B503192DC25F419D1E93EB7FFAC666` |

## Метадані

- **Ім'я файлу:** `igdkmdnd64_4.sys`
- **Розмір:** 54575208 bytes
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
