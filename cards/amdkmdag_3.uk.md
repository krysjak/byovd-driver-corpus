# `amdkmdag_3.sys`

[Назад до індексу](../README.uk.md) · [English version](amdkmdag_3.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `8114A73C2AF7E90FE98B18E299D2683EF1371893250023DFD0463FA1097E86E1` | `11909A3661EACC565C34C12F38940B2E5705B383` | `62C2BFE0A1EF90054145F24F921AAF24` |

## Метадані

- **Ім'я файлу:** `amdkmdag_3.sys`
- **Розмір:** 71113752 bytes
- **Архітектура:** 0x8664
- **Компанія:** Advanced Micro Devices, Inc.
- **Продукт:** ATI Radeon Family
- **Опис:** ATI Radeon Kernel Mode Driver
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** —
- **У системах:** OEM package
- **Score:** 160

## Профіль можливостей

**Primitives:** `MDL allocation`, `driver loading`, `page locking`, `physical address resolution`, `physical memory mapping`, `process handle access`, `process lookup`, `process termination`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmMapIoSpace`, `MmProbeAndLockPages`, `PsLookupProcessByProcessId`, `ZwLoadDriver`, `ZwOpenProcess`, `ZwTerminateProcess`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
