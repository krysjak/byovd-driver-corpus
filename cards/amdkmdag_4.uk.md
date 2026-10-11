# `amdkmdag_4.sys`

[Назад до індексу](../README.uk.md) · [English version](amdkmdag_4.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `D4CD8F1B0CE61F69150209F44B4F119DE3E7781A6F049561787E29EC041C5F0C` | `752F60E98E97A9B103A9C13224DFA87E5E260D1D` | `DFC9FE9A0AFD33486211C74EBD13BA90` |

## Метадані

- **Ім'я файлу:** `amdkmdag_4.sys`
- **Розмір:** 80459656 bytes
- **Архітектура:** 0x8664
- **Компанія:** Advanced Micro Devices, Inc.
- **Продукт:** ATI Radeon Family
- **Опис:** ATI Radeon Kernel Mode Driver
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** — · **Немає перевірки probe:** —
- **У системах:** OEM package
- **Score:** 150

## Профіль можливостей

**Primitives:** `MDL allocation`, `driver loading`, `page locking`, `physical address resolution`, `physical memory mapping`, `process handle access`, `process lookup`, `process termination`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmMapIoSpace`, `MmProbeAndLockPages`, `PsLookupProcessByProcessId`, `ZwLoadDriver`, `ZwOpenProcess`, `ZwTerminateProcess`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
