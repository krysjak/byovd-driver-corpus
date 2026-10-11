# `amdkmdag_2.sys`

[Назад до індексу](../README.uk.md) · [English version](amdkmdag_2.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `C482A327377F028C8DBD7BE1FDFD32C0A9F1F2E21C8BC3BE5F0F07DE14A3AFA4` | `21F53AA5DB675199332C559A26755B304FD8521D` | `45FA307026081AA1F8353AC93F6B80DD` |

## Метадані

- **Ім'я файлу:** `amdkmdag_2.sys`
- **Розмір:** 100367472 bytes
- **Архітектура:** 0x8664
- **Компанія:** Advanced Micro Devices, Inc.
- **Продукт:** ATI Radeon Family
- **Опис:** ATI Radeon Kernel Mode Driver
- **Підпис:** signed
- **Джерело:** `oem:hp`
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
