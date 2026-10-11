# `igdkmd32.sys`

[Назад до індексу](../README.uk.md) · [English version](igdkmd32.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `438DF853487C52FC312717E6C051E02431843DB28E5205BA58792FC1EE7BA60B` | `5732597A65D026A63274656B854FDF943AE5E788` | `F44C39688CAD7B5A49C26154A11B2A89` |

## Метадані

- **Ім'я файлу:** `igdkmd32.sys`
- **Розмір:** 3035568 bytes
- **Архітектура:** 0x14c
- **Компанія:** Intel Corporation
- **Продукт:** Intel HD Graphics Drivers for Windows 8(R)
- **Опис:** Intel Graphics Kernel Mode Driver
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** — · **Немає перевірки probe:** —
- **У системах:** OEM package
- **Score:** 160

## Профіль можливостей

**Primitives:** `MDL allocation`, `contiguous physical allocation`, `driver loading`, `page locking`, `physical address resolution`, `physical memory mapping`, `process lookup`, `section mapping (kernel R/W surface)`

**Imports:** `IoAllocateMdl`, `MmAllocateContiguousMemory`, `MmGetPhysicalAddress`, `MmMapIoSpace`, `MmProbeAndLockPages`, `PsLookupProcessByProcessId`, `ZwLoadDriver`, `ZwMapViewOfSection`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
