# `igdkmdnd64_6.sys`

[Назад до індексу](../README.uk.md) · [English version](igdkmdnd64_6.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `77C6607EB482E47369EE9CF4F44420D336B46F3264DEEBFBA99ABA5A82FAC66D` | `5E6E88E33475231EA22C9802CB231B4FF684927E` | `72C35330125F3C085EB6B79A0EAC04F4` |

## Метадані

- **Ім'я файлу:** `igdkmdnd64_6.sys`
- **Розмір:** 31329904 bytes
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
